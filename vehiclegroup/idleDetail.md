Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/idledetail?session_token=xxxx&vehicle_group=Delivery&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
      {
        id: "CA4531009XXX",
        vin: "2C4RDGCG2ER173XXX",
        label: "Truck 173",
        latitude: 33.358263,
        longitude: -111.9158031,
        landmark_id: 27404,
        landmark: "James1",
        proximity: 39,
        odometer: 133070.6,
        trip_start_adj: "Aug 1 2015 09:00:14",
        trip_end_adj: "Aug 1 2015 09:02:14",
        GHG: "0.0001236183971370",
        co2_rate: 0.008809,
        fuel_type: "U",
        idle_gal: 0.014033193,
        idle_gph: 0.421,
        sec_duration: 120,
        true_idle: 120
      }, { ... }
      ]
    }
