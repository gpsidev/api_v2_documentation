Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/scorecard?session_token=xxxx&group=XXXX&timeframe=week

Example Response:

    {
      head: { .... },
      data: [
        {
            "id": "CAXXXXXXXXXXXX",
            "vin": "1BXXXXXXXXXXXX",
            "label": "XXXX-XX",
            "serial_number": XXXXXXXXXX,
            "score": 100,
            "rating": "good",
            "certified": false,
            "miles_driven": 56.6,
            "runtime_minutes": 185,
            "daily_scores": [
                {
                    "date": "2019-02-26",
                    "score": 79.85,
                    "rating": "good"
                }
            ],
            "events": [
                {
                    "name": "hard braking",
                    "count": 1,
                    "rating": "good"
                },
                {
                    "name": "hard left",
                    "count": 2,
                    "rating": "good"
                },
                {
                    "name": "hard right",
                    "count": 2,
                    "rating": "good"
                },
                {
                    "name": "rapid acceleration",
                    "count": 4,
                    "rating": "good"
                },
                {
                    "name": "speeding",
                    "count": 2,
                    "rating": "good"
                }
            ]
        },
        {
            "id": "CAXXXXXXXXXXXX",
            "vin": "2BXXXXXXXXXXXX",
            ....
        }
      ]
    }
