Example Request:

https://api.gpsinsight.com/v2/vehicle/locationhistorical?session_token=xxxx&vehicle=CA4531009XXX&time=12:13:08

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          vin: "5FNRL38487803XXXX",
          label: "Truck 149",
          serial_number: 453100XXXX,
          age_minutes: 26671,
          fix_time: "8/2/15 03:00:01",
          fix_time_mst: "8/2/15 03:00:01 MST",
          fix_time_gmt: "2015-08-02T10:00:01+00:00",
          latitude: 33.63273,
          longitude: -111.97923,
          landmark_id: 972034,
          landmark: "Loading Station 2",
          heading: 0,
          ignition: " ",
          max_speed: "0",
          avg_speed: 0,
          inst_speed: 0,
          speed_label: "Out of Range 18 days",
          speed_icon: "orange_dot_inputs",
          odometer: 57173.7,
          driver_id: 4551485,
          first_name: "Tom",
          last_name: "Gypsy"
        }
      ]
    }
