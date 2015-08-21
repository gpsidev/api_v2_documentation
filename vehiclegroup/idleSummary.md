Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/idlesummary?session_token=xxxx&vehicle_group=Delivery&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
      {
        id: "CA4531009XXX",
        vin: "2C4RDGCG2ER173XXX",
        label: "Truck 174",
        serial_number: 45310090XX,
        max_speed: 80,
        avg_speed: 19,
        speed_label: "80 mph (max)",
        speed_icon: "bright_green_dot",
        GHG: "0.0044709080118950",
        co2_rate: 0.008809,
        fuel_type: "U",
        idle_avg: 7,
        idle_cnt: 10,
        idle_gal: 0.507538655,
        idle_gph: 0.421,
        idle_max: 18,
        idle_minutes: 71,
        idle_pct: "39.754511312631671",
        move_minutes: 180,
        total_miles: 41.4,
        true_idle: 4340,
        true_idle_gal: 0.507538888889,
        true_idle_GHG: 0.00447091007222,
        true_idle_pct: 39
      }, { ... }
      ]
    }
