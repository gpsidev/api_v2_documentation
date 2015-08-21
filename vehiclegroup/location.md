Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/location?session_token=xxxx&vehicle_group=Delivery

Example Response:

    {
      head: { .... },
      data: [
      {
        id: "CA4641163XXX",
        vin: "CA4641163XXX",
        label: "Truck 201",
        serial_number: 4641163XXX,
        age_minutes: 45834,
        fix_time: "7/20/15 14:56:56",
        fix_time_mst: "7/20/15 14:56:56 MST",
        fix_time_gmt: "2015-07-20T21:56:56+00:00",
        exec_time: "2015-08-21T17:51:23+00:00",
        latitude: 33.65942,
        longitude: -111.92482,
        landmark_id: 910482,
        landmark: "Headquarters",
        heading: 331,
        ignition: "off",
        max_speed: 0,
        avg_speed: 0,
        inst_speed: 0,
        speed_label: "Stopped 31 days",
        speed_icon: "red_dot",
        odometer: 1682.6
      }, { ... }
      ]
    }
