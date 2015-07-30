Get a list of all canned messages by message type. 
  * Example: 
    * http://api.gpsinsight.com/v2/garmin/listCannedMessages?&token=authToken&message_type=X
  * Response:

    {
    head: { ... },
    data: [
    {   type: "Message",
        message: "Test Message2",
        message_id: 502997,
        garmin_message_id: 54500,
        seq: 578,
        created: "6/24/14 8:30:30 AM" 
    }, 
    {...},
    {...}
    ]}
    
