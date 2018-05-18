Trip Types:

In the response there is a trip_type field with the following codes:
 * T - Trip measured from ignition-on to idle-start or ignition-off, or idle-stop to idle-start to ignition-off
 * I - Idle measured as ignition-on and zero-speed
 * S - Stop measured as ignition-off
 
Example Request:

https://api.gpsinsight.com/v2/vehicle/tripdetail?session_token=xxxx&vehicle=CA4531009XXX&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4542138625",
          label: "Truck 149",
          serial_number: 454213XXXX,
          max_speed: 69,
          avg_speed: 23,
          speed_label: "23 mph",
          speed_icon: "bright_green_dot",
          driver_id: 414,
          ref_id: "8489",
          driver_first_name: "Jon",
          driver_last_name: "Snow",
          trip_type: "T",
          trip_start: "May  8 2015 08:44:47",
          trip_end: "May  8 2015 08:53:54",
          duration: 0.15,
          distance: 3.8,
          latitude_start: 33.4524453,
          longitude_start: -111.6850295,
          latitude_end: 33.4391695,
          longitude_end: -111.6301206,
          points: 5,
          in_progress: 0,
          min_latitude: 33.436704,
          min_longitude: -111.6851675,
          max_latitude: 33.4524453,
          max_longitude: -111.6301206,
          fastest_distance: 3.77,
          fastest_hours: 0.11,
          shortest_distance: 3.76,
          shortest_hours: 0
        },
        {
          id: "CA4542138625",
          label: "Monstro",
          serial_number: 454213XXXX,
          driver_id: 414,
          ref_id: "8489",
          driver_first_name: "Jon",
          driver_last_name: "Snow",
          trip_type: "S",
          trip_start: "May  8 2015 22:02:48",
          trip_end: "May  9 2015 05:30:54",
          duration: 7.47,
          latitude_start: 33.4392068,
          longitude_start: -111.6300613,
          latitude_end: 33.4392068,
          longitude_end: -111.6300613,
          in_progress: 0
        }, { ... }
      ]
    }
