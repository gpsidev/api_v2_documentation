Description and examples for /v2/geocode/reverse to follow...
Reverse geocode an address from a latitude and longitude  

  * Example:
    * http://api.gpsinsight.com/v2/geocode/reverse?latitude=X&longitude=X&heading=X
  * Response:

    {
    head: { ... },
    data: {
        country: "USA",
        speed_limit: 45,
        speed_limit_unit: "MPH",
        county: "Maricopa",
        street_number: "19010",
        street: "N Scottsdale Rd",
        city: "Phoenix",
        us_state: "AZ",
        zip_code: "85255",
        meta: {
            formatted: "19010 N Scottsdale Rd, Phoenix, AZ 85255",
            road_lanes: "6",
            road_usage: "Arterial",
            distance: "52.279258",
            score: 10
        }
    }}
