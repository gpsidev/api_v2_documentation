Example Request:

https://api.gpsinsight.com/v2/vehicle/idledetail?session_token=xxxx&vehicle=CA4531009XXX&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          vin: "5FNRL38487803XXXX",
          label: "Truck 203",
          latitude: 33.659575,
          longitude: -111.9248385,
          landmark_id: 910482,
          landmark: "Headquarters",
          proximity: 51,
          odometer: 56844.6,
          driver_id: 45514XX,
          first_name: "Tom",
          last_name: "Gypsy",
          trip_start_adj: "Jul 15 2015 16:43:02",
          trip_end_adj: "Jul 15 2015 16:45:02",
          GHG: "0.0001206820931670",
          co2_rate: 0.008809,
          idle_gal: 0.013699863,
          idle_gph: 0.411,
          sec_duration: 120
        }
      ]
    }
