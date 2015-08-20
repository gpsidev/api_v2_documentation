Example Request:

https://api.gpsinsight.com/v2/hierarchynode/list?session_token=xxxx&node=NE&tree=Division

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA433107XXXX",
          vin: "433107XXXX",
          label: "DG-Juke",
          serial_number: 433107XXXX,
          age_minutes: 27028,
          fix_time: "Aug 1 2015 14:18:09",
          fix_time_mst: "Aug 1 2015 14:18:09",
          exec_time: "Aug 20 2015 08:46:33",
          latitude: 33.58671,
          longitude: -111.84235,
          landmark_id: 935604,
          landmark: "Vehicle Yard",
          heading: 107,
          ignition: "off",
          max_speed: 0,
          avg_speed: 0,
          inst_speed: 0,
          odometer: 5497.9,
          voltage: 14.9,
          driver_id: 404XXXX,
          first_name: "Amanda",
          last_name: "Gray",
          phone_number: "480689XXXX"
        }, { ... }
      ]
    }
