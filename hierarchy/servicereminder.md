Example Request:

https://api.gpsinsight.com/v2/hierarchy/serviceReminder?session_token=xxxx&tree=division&date=03/18/2021

Example Response:

    {
    head: { .... },
    data: {
        "CA4542133359": {
            "id": "CA4542133359",
            "status": "overdue",
            "reminders": [
                {
                    "maint_alert_id": 39525,
                    "maint_label": "Oil Change / Tire Rotation",
                    "status": "overdue",
                    "diff_svc_value": -13803,
                    "next_svc_value": 190500,
                    "diff_svc_date": 42214951,
                    "next_svc_date": "2019-11-27 00:00:00",
                    "diff_svc_hrs": 73.76099999999997,
                    "next_svc_hrs": 2359
                }
            ]
        },
        "CA4572199523": {
            "id": "CA4572199523",
            "status": "good",
            "reminders": [
                {
                    "maint_alert_id": null,
                    "maint_label": null,
                    "status": "good"
                }
            ]
        },
    }
    
