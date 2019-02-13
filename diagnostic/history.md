Example Request:

https://api.gpsinsight.com/v2/diagnostic/history?session_token=xxxx&vehicle=CA41XXXXXXX&start=2019-01-14&end=2019-01-16&code=Accel+Event

Example Response:

    {
      head: { .... },
      data: [
         {
             "code": "Accel Event",
             "value": "'Hard Braking'",
             "received_date": "2019-01-15 07:32:59"
         }
      ]
    }
