Example Request:

https://api.gpsinsight.com/v2/alert/read?session_token=xxxx&alert=19761

Example Response: 

    {
        head: { .... },
        data: [
            {
                watcher_id: 19761,
                instance_description: "IDLE ALERT",
                active: 1,
                watcher_type: "idle"
            }
        ]
    }
