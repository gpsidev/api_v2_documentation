The `webhook` endpoint allows users to define and manage webhooks. There is also a web interface for this. 
On the Portal main menu, go to Account->Manage Webhooks.

### Push vs. Pull
Webhooks allow us to push data to your servers as soon as we collect it (PUSH), 
instead of you periodically requesting data from our API (PULL).
You will specify a public endpoint on one of your web servers, and we will post data to it securely. 
If you request a `Location` data, you should expect to receive data almost constantly while your fleet is driving.  

When a webhook is established, we expect you to be able to consume the data constantly while we push it to you.
Points will be sent one at a time on a single channel. 
The next point will be sent as soon as we get an HTTP response from the point before.

On our side, we put your points into a queue, so we can guarantee delivery of each point.
 * If your service returns an HTTP error code, we will assume you did not receive the message, 
and we will re-queue the message for delivery.
 * If your service is unavailable, we will also re-queue the message for delivery.
 * If your service does not consume points as quickly as they are queued, the queue may fill up.

You can use the API's `/webhook/list` function to see all your queues, their status and their queue depth.

### Queue Pausing
With multiple customers using webhooks, we cannot queue points indefinitely, 
so we will pause your queue when the queue depth reaches **5000 points**.
This is usually an indication of a persistent problem on your side, 
or you are not processing points as quickly as they are being queued.

If your queue is paused, the contact email you specified when you created the webhook will be notified, 
and your queue will be flushed. You can resume the queue using the api's `/webhook/resume` function.
  
If you are consuming the `Location` webhook, 
and you feel it's important to recover data from a period of time your queue was paused,
you can use the api's `/vehicle/history` function with a specific time period to receive the same points.

### Recommended Setup
Consuming a `Location` webhook can sometimes be like drinking from a firehose. 
There is the potential for **a lot** of data to be coming at you very quickly. 
It is important that you are set up to receive and persist that data as quickly as possible.
This model is similar to how we receive our own data from tracking devices, 
so we have some suggestions on how to set up your systems for optimal performance.
 
We recommend you set up a **separate data collection service** that's completely independent of your business services, 
whose function is just to receive and persist this data in some kind of data store. 
Your business systems would then look in that data store for data, rather than trying to consume the webhook data directly.

We recommend that you take steps to ensure that this data collection service **never goes down**.
If you have maintenance windows for your business systems, try not to have those service windows affect the data collection.
If your data collection service goes down, it will be harder to catch up, and you may fill your buffer.

We recommend you **buffer data** in your data collection service to ensure you get everything quickly.
Think of the fastest way possible for you to persist data, buffer it there, and respond to our post,
then process data out of that buffer at your own pace. This will keep the data flowing.
  
