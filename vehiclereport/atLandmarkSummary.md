Example Request:

https://api.gpsinsight.com/v2/vehiclereport/closesttolandmark?session_token=xxxx&landmark_group=21771&group=3838&radius=8800&rows=2

Example Response:

    {
      head: { .... },
      data: [
        {
          landmark_id: 790948,
          name: "Airport",
          number: 3,
          latitude: 33.4330887,
          longitude: -112.0059585
        }, { ... }
      ]
    }
