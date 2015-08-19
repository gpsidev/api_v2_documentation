Example Request:

https://api.gpsinsight.com/v2/geocode/timezone?session_token=xxxx&latitude=33.333&longitude=-111.111

Example Response:

    {
      head: { .... },
      data: [
        {
          tz_id: 1,
          country: "us",
          name: "US/Arizona",
          offset: -25200,
          display_code: "MST",
          display_string: "-0700",
          latitude: "34.444",
          longitude: "-111.111"
        }
        {
          tz_id: 3,
          country: "us",
          name: "US/Central",
          offset: -18000,
          display_code: "CDT",
          display_string: "-0500",
          latitude: "33.333",
          longitude: "-100.000"
        }
      ]
    }
