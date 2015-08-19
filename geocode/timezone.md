Example Request: https://api.gpsinsight.com/v2/geocode/timezone?session_token=xxxx&latitude=33.333&longitude=-111.111

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
display_string: "-0700"
            }
        ]
    }
