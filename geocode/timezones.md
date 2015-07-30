Description and examples for /v2/geocode/timezones to follow...
Geocode a set of points into specific timezones
  * Example:
    * http://api.gpsinsight.com/v2/geocode/timezones?&points[0][0]=33.333&points[0][1]=-100.000&points[1][0]=34.444&points[1][1]=-111.111
    * 
  * Response:

    {
    head: { ... },
    data: [
    {   name: "US/Pacific",
        gmt_offset_seconds: -25200,
        display_offset: "-0700",
        display_code: "PDT",
        latitude: "34.444",
        longitude: "-119.222"
    },{ name: "US/Arizona",
        gmt_offset_seconds: -25200,
        display_offset: "-0700",
        display_code: "MST",
        latitude: "34.444",
        longitude: "-111.111"
    },{ name: "US/Central",
        gmt_offset_seconds: -18000,
        display_offset: "-0500",
        display_code: "CDT",
        latitude: "33.333",
        longitude: "-100.000"
    }]}
