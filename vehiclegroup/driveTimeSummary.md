Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/drivetimesummary?session_token=xxxx&vehicle_group=Delivery&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: {
        CA45420425361438496XXX: {
        id: "CA4542042XXX",
        vin: "KNMAT2MT8FP51XXXX",
        label: "Truck 120",
        serial_number: 4542042536,
        fix_time_mst: "8/1/15 23:25:00 MST",
        fix_time_gmt: "2015-08-02T06:25:00+00:00",
        max_speed: 82,
        avg_speed: 48,
        speed_label: "82 mph (max)",
        speed_icon: "bright_green_dot",
        stops: 8,
        distance: 57,
        points: 54,
        day_count: 1,
        total_travel_time: 9135,
        total_idle_time: 2663,
        first_start: "Aug 1 2015 11:43:38",
        last_stop: "Aug 1 2015 23:25:55",
        last_update: "Aug 1 2015 23:25:55"
        }, { ... }
      }
    }
