Description and examples for /v2/geocode/timezone to follow...
Geocode a point into a specific timezone
  * Example:
    * http://api.gpsinsight.com/v2/geocode/timezone?&latitude=33.333&longitude=-111.111
  * Response:

    {
    head: { ... },
    data: {
        name: "US/Arizona",
        gmt_offset_seconds: -25200,
        display_offset: "-0700",
        display_code: "MST"
    }}
