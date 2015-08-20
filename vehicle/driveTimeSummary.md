Example Request:

https://api.gpsinsight.com/v2/vehicle/drivetimesummary?session_token=xxxx&vehicle=CA4531009036&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA453100XXXX",
          vin: "5FNRL38487803XXXX",
          label: "Truck 3089",
          serial_number: 453100XXXX,
          fix_time_mst: "8/2/15 03:00:00 MST",
          fix_time_gmt: "2015-08-02T10:00:00+00:00",
          max_speed: 56,
          avg_speed: 27,
          speed_label: "56 mph (max)",
          speed_icon: "green_dot",
          driver_id: 45514XX,
          first_name: "Tom",
          last_name: "Gypsy",
          stops: 2,
          distance: 7.5,
          points: 8,
          day_count: 1,
          total_travel_time: 1656,
          total_idle_time: 406,
          first_start: "Aug 1 2015 13:56:29",
          last_stop: "Aug 1 2015 15:33:03",
          last_update: "Aug 2 2015 03:00:01"
        }
      ]
    }
