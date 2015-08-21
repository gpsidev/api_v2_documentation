Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/postedspeed?session_token=xxxx&vehicle_group=Delivery&start=8/1/2015&end=8/3/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4542042XXX",
          vin: "KNMAT2MT8FP514XXX",
          label: "Truck 135",
          age_minutes: 28672,
          fix_time_mst: "8/1/15 12:09:55 MST",
          fix_time_gmt: "2015-08-01T19:09:55+00:00",
          latitude: 33.42268,
          longitude: -111.67814,
          heading: 94,
          ignition: "on",
          max_speed: 57,
          avg_speed: 14,
          inst_speed: 55,
          speed_limit: 45,
          speed_label: "Out of Range 19 days",
          speed_icon: "orange_dot",
          odometer: 7187.3,
          percent_over: 20,
          violation: 10
        }, { ... }
      ]
    }
