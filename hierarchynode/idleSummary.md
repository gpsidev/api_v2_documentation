Example Request:

https://api.gpsinsight.com/v2/hierarchynode/idlesummary?session_token=xxxx&tree=Division&node=West&start=8/1/2015&end=8/15/2015&idle_min=2

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          vin: "5FNRL38437B40XXXX",
          label: "Truck 140",
          serial_number: 453100XXX,
          max_speed: 56,
          avg_speed: 11,
          driver_id: 1009582,
          first_name: "Lonny",
          last_name: "Anders",
          GHG: "0.0001206820931670",
          co2_rate: 0.008809,
          fuel_type: "U",
          idle_avg: 2,
          idle_cnt: 1,
          idle_gal: 0.013699863,
          idle_gph: 0.411,
          idle_max: 2,
          idle_minutes: 2,
          idle_pct: "1.7318516380430076",
          move_minutes: 115,
          total_miles: 46.2
        }, { ... }
      ]
    }
