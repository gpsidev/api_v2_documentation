Example Request:

https://api.gpsinsight.com/v2/hierarchy/lifetimeUtilization?session_token=xxxx&tree=division

Example Response:

    {
      head: { .... },
      data: [
            {
                "id": "CA1243017699",
                "vin": "12345678901234567",
                "run_days": 113,
                "run_minutes": 1779,
                "stop_minutes": 16509,
                "idle_minutes": 1761,
                "miles_driven": 314.6,
                "max_mph": 85,
                "avg_mph": 11
            },
            {
                "id": "CA1243137549",
                "vin": "1243127549",
                "run_days": 135,
                "run_minutes": 74,
                "stop_minutes": 24718,
                "idle_minutes": 8,
                "miles_driven": 1,
                "max_mph": 68,
                "avg_mph": 19
            }
        ]
    }
