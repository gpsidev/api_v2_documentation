Example Request:

https://api.gpsinsight.com/v2/vehiclereport/closesttovin?session_token=xxxx&vin=5TDXK3DC4DS35XXXX&group=3838&radius=800

Example Response:

    {
      head: { .... },
      data: [
        {
          vin: "5TDXK3DC4DS35XXXX",
          vin2: "123456",
          vehicle: "Truck 193",
          vehicle_id: 253XXX,
          trailer: 0,
          is_asset: 0,
          fname: null,
          lname: null,
          refid: null,
          alert_pref: 0,
          phone_number: null,
          email_address: null,
          date: "Jul 14, 2015",
          time: "03:00",
          ageMinutes: 64470,
          fix_time_adj: "Jul 14 2015 3:00AM",
          fix_time_utf: "Jul 14 2015 3:00AM",
          latitude: 33.6595,
          longitude: -111.9249,
          ignition: " ",
          speed: "0",
          speed_units: "MP",
          peed_type: "Max",
          heading: 313,
          distance: 363,
          has_garmin: 1,
          formattedDistance: "0.1 mi.",
          formattedTime: "1 min",
          formattedDriveDistance: "0.2 mi.",
          formattedVehicle: "Truck 193"
        }, { ... }
      ]
    }
