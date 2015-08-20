Example Request:

https://api.gpsinsight.com/v2/hierarchynode/idledetail?session_token=xxxx&tree=Division&node=West&start=08/01/2015&end=08/15/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA453100XXXX",
          vin: "5FNRL38437B40XXXX",
          label: "Truck 1489",
          latitude: 33.3469536,
          longitude: -111.7825448,
          landmark_id: 963560,
          landmark: "Headquarters",
          proximity: 42,
          odometer: 174857.3,
          driver_id: 1009582,
          first_name: "Mike",
          last_name: "Jones",
          trip_start_adj: "Aug 1 2015 11:15:13",
          trip_end_adj: "Aug 1 2015 11:17:12",
          GHG: "0.0001196755944450",
          co2_rate: 0.008809,
          fuel_type: "U",
          idle_gal: 0.013585605,
          idle_gph: 0.411,
          sec_duration: 119
        }, { ... }
      ]
    }
