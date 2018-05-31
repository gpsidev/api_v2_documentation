Example Request:

https://api.gpsinsight.com/v2/vehicle/lastTripMap?session_token=xxxx&vehicle=CA4531009036&width=600&height=600

Example Response:

    {
      head: { .... },
      data: {
        "last_trip_map": "https://www.gpsinsight.com/report/getTripMap.php?m=xxxxxxxxxxxxx&width=600&height=600"
      }
    }
