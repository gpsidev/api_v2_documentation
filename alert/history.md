Example Request:
https://api.gpsinsight.com/v2/alert/history?session_token=xxxx&vehicle=CA4531009036&alert=19761&alert_minutes_age=3000

Example Response:

    {
        head: { .... },
        data: [
            {
                id: "CA453100903",
                vin: "XXXXXXXXX",
                label: "FLEETVAN1",
                serial_number: 22222222222,
                fix_time: "Aug 14 2015 10:22PM",
                alert_id: 19761,
                alert_type: "Idle Time",
                description: "IDLE ALERT",
                alert_condition: "FLEETVAN1 idled 15 min (15 min threshold)",
                alert_recipients: "email@example.com",
                alert_date: "Aug 14 2015 10:23PM"
            }
        ] 
    }
