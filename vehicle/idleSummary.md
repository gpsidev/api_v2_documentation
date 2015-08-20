Example Request:

https://api.gpsinsight.com/v2/vehicle/idlesummary?session_token=xxxx&vehicle=CA4531009XXX&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          vin: "5FNRL384878031XXX",
          label: "Truck 289",
          serial_number: 4531009036,
          max_speed: 63,
          avg_speed: 22,
          speed_label: "63 mph (max)",
          speed_icon: "green_dot",
          driver_id: 4551485,
          first_name: "Tom",
          last_name: "Gypsy",
          GHG: "0.0001206820931670",
          co2_rate: 0.008809,
          idle_avg: 2,
          idle_cnt: 1,
          idle_gal: 0.013699863,
          idle_gph: 0.411,
          idle_max: 2,
          idle_minutes: 2,
          idle_pct: "6.6334991708126037",
          move_minutes: 30,
          total_miles: 10.9
        }
      ]
    }
