Note: One of the following parameters is required (street address or latitude and longitude). The mapbook feature has limited availability.

Example Request:

https://api.gpsinsight.com/v2/geocode/mapbook?session_token=xxxx&latitude=33.333&longitude=-111.111

Example Response:

    {
      head: { .... },
      data: {
            country: "USA",
            county: "Pinal",
            street: "Silver King Mine Rd",
            city: "Superior",
            us_state: "AZ",
            zip_code: "85173",
            heading: "-1",
            ds: "navteq",
            meta: {
                formatted: "Silver King Mine Rd, Superior, AZ 85173",
                road_lanes: "1",
                road_usage: "Local Street",
                distance: "3313.625479",
                score: 8
            }
        }
    
    }
