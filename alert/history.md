Example:

    {
        head: { .... },
        data: [
            {
                id: "CA4331000000",
                vin: "XXXXXXXXX",
                label: "FLEETVAN1",
                serial_number: 22222222222,
                alert_id: 10597,
                alert_type: "Idle Time",
                description: "IDLE ALERT",
                alert_condition: "FLEETVAN1 idled 15 min (15 min threshold)",
                alert_recipients: "email@example.com",
                alert_date: "Oct 31, 2014  10:31AM"
            },
            {
                id: "CA4331000003",
                vin: "XXXXXXXXX",
                label: "FLEETVAN3",
                serial_number: 333333333333,
                alert_id: 10597,
                alert_type: "Speeding",
                description: "SPEEDING ALERT",
                alert_condition: "FLEETVAN3 going 86 mph (80 mph threshold)",
                alert_recipients: "email@example.com",
                alert_date: "Oct 31, 2014  10:31AM"
            }
        ] }
