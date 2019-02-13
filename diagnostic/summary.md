Example Request:

https://api.gpsinsight.com/v2/diagnostic/summary?session_token=xxxx&vehicle=CA41XXXXXXX&start=2019-01-14&end=2019-01-16

Example Response:

    {
      head: { .... },
      data: [
         {
             "code": "Coolant Temp",
             "description": "Coolant Temp",
             "value_count": 309,
             "max_value": 206.6,
             "min_value": 32,
             "first_date": "2019-01-15 05:01:28",
             "last_date": "2019-01-20 20:01:40"
         }
      ]
    }
