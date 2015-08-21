Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/beginendday?session_token=xxxx&vehicle_group=Delivery&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4331022808",
          vin: "483020c90XXXX",
          label: "Truck 203",
          serial_number: 4331022XXX,
          odometer: 213601.7,
          trips: 2,
          date: "08/01/2015",
          start_time: "12:28:19",
          end_time: "22:15:57",
          duration: 35258,
          trip_duration: 2765,
          distance: 32.5,
          max_speed: 80,
          avg_speed: 23,
          start_latitude: 33.4456735,
          start_longitude: -111.991547,
          start_landmark_id: 790948,
          start_landmark_name: "Airport",
          end_latitude: 33.7540906,
          end_longitude: -111.9378086
        }, { ... }
      ]
    }
