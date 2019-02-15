Example Request:

https://api.gpsinsight.com/v2/diagnostic/listAll?session_token=xxxx&vehicle=CA41XXXXXXX

Example Response:

    {
      head: { .... },
      data: [
         {
            "code": "B282F",
            "first_date": "2017-07-26 21:06:32",
            "last_date": "2017-08-09 07:11:53"
         }
      ]
    }
