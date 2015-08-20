Example Request:

https://api.gpsinsight.com/v2/vehicle/postedspeed?session_token=xxxx&vehicle=CA4531009XXX&start=7/1/2015+12:00:00&end=8/15/2015+22:00:00

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          vin: "5FNRL38487803XXXX",
          label: "Truck 149",
          age_minutes: 54647,
          fix_time_mst: "7/13/15 16:46:05 MST",
          fix_time_gmt: "2015-07-13T23:46:05+00:00",
          latitude: 33.65141,
          longitude: -111.97744,
          heading: 180,
          ignition: "on",
          max_speed: 57,
          avg_speed: 37,
          inst_speed: 55,
          speed_limit: 45,
          speed_label: "Out of Range 37 days",
          speed_icon: "black_dot",
          odometer: 56825.6,
          driver_id: 45514XX,
          first_name: "Tom",
          last_name: "Gypsy",
          percent_over: 20,
          violation: 10
        }, { ... }
      ]
    }
