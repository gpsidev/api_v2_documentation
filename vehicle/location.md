Example request:

https://api.gpsinsight.com/v2/vehicle/location?session_token=xxxx&vehicle=CA4531009XXX


Example response: 

    {
    head: { ... },
    data: [
      {
        id: "VVYYYYYYYYYY",
        vin: "XXXXXXXXXXXXXXXXX",
        label: "060199",
        serial_number: YYYYYYYYYY,
        age_minutes: 493,
        timezone: "MST",
        fix_time: "8/14/15 7:27:10 AM",
        fix_time_mst: "8/14/15 7:27:10 AM MST",
        fix_time_gmt: "2015-08-14T14:27:10+00:00",
        exec_time: "2015-08-14T22:40:15+00:00",
        latitude: 33.6604276,
        longitude: -111.924858,
        landmark_id: 88802,
        landmark: "GPS Insight Headquarters",
        address: "19179 N Scottsdale Rd, Scottsdale, AZ 85255",
        heading: 16,
        ignition: "off",
        max_speed: 0,
        avg_speed: 0,
        inst_speed: 0,
        speed_limit: 45,
        speed_label: "Stopped 8 hrs, 13 min",
        speed_icon: "red_dot",
        odometer: "38616.3",
        voltage: "12.2",
        driver_id: "1",
        first_name: "Dwight",
        last_name: "Eisenhower",
        phone_number: "4806639454"
      }
    ]}
