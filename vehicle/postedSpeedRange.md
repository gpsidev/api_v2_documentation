Counts of posted speed violations will be returned in three different ranges for each vehicle. 
For each range, the high and low values define the violation range, and the count is the number of violations.

For example, {"low":10, "high":15, "count":169} means there were 169 posted speed violations between 10 mph and 15 mph.

Example Request:

https://api.gpsinsight.com/v2/vehicle/postedSpeedRange?session_token=xxxx&vehicle=CA4531009XXX&start=3/1/2019&end=3/15/2019

Example Response:

    {
        "head": { ... },
        "data": 
        [
            {
                "id": "CA4531009XXX",
                "vin": "5LMJJ3J51DEL04937",
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
            }
        ]
    }
