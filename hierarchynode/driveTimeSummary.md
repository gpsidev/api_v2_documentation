Example Request:

https://api.gpsinsight.com/v2/hierarchynode/drivetimesummary?session_token=xxxx&tree=Division&node=West&start=08/01/2015&end=08/15/2015

Example Response:

    {
      head: { .... },
      data: {
        CA43320957501438509600: {
        id: "CA433209XXXX",
        vin: "1FMZU63K54ZA48960",
        label: "Truck 208",
        serial_number: 4332095750,
        fix_time_mst: "Aug 2 2015 3:00AM",
        max_speed: 75,
        avg_speed: 46,
        stops: 5,
        distance: 54.1,
        points: 42,
        day_count: 1,
        total_travel_time: 4960,
        total_idle_time: 0,
        first_start: "Aug 1 2015 06:31:16",
        last_stop: "Aug 1 2015 15:45:00",
        last_update: "Aug 2 2015 03:00:01"
        }, { ... }
      }
    }
