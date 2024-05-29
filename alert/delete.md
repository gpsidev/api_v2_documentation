This will permanently delete the alert. If you wish to temporarily disable an alert instead, 
use the corresponding update method for the alert and set the `active` parameter to `0`.

Example Request:

https://api.gpsinsight.com/v2/alert/delete?session_token=xxxx&alert_id=19761

Example Response: 

    {
        head: { .... },
        data: true
    }
