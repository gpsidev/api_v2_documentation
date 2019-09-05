Counts of posted speed violations will be returned in three different ranges for each vehicle. 
For each range, the high and low values define the violation range, and the count is the number of violations.

For example, {"low":10, "high":15, "count":169} means there were 169 posted speed violations between 10 mph and 15 mph.

Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/postedSpeedRange?token=0f11bf5f6b15&start=4/1/2019&end=5/1/2019&group=ALL%20VEHICLES

Example Response:

    {
        "head": { ... },
        "data": 
        [
            {
                "id": "CA4531009XXX",
                "vin": "5LMJJ3J51DE",
                "label": "8004-03",
                "range": [
                    {
                        "low": 10,
                        "high": 15,
                        "count": 169
                    },
                    {
                        "low": 16,
                        "high": 21,
                        "count": 9
                    },
                    {
                        "low": 22,
                        "high": 99,
                        "count": 0
                    }
                ]
            },
            {
                "id": "CA367100XXX",
                "vin": "GETVES00274",
                "label": "8734-03",
                "range": [
                    {
                        "low": 10,
                        "high": 15,
                        "count": 0
                    },
                    {
                        "low": 16,
                        "high": 21,
                        "count": 0
                    },
                    {
                        "low": 22,
                        "high": 99,
                        "count": 0
                    }
                ]
            },
            { ... }
        ]
    }
