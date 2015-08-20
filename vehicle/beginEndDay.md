Example Request:

https://api.gpsinsight.com/v2/vehicle/beginendday?session_token=xxxx&vehicle=Truck%20240&start=08/01/2015+12:00:00&end=08/02/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA453100XXXX",
          vin: "5FNRL38487803XXXX",
          label: "Truck 240",
          serial_number: 453100XXXX,
          odometer: 57173.7,
          driver_id: 45514XX,
          first_name: "Tom",
          last_name: "Gypsy",
          trips: 2,
          date: "08/01/2015",
          start_time: "13:56:29",
          end_time: "15:33:03",
          duration: 5794,
          trip_duration: 1656,
          distance: 7.5,
          max_speed: 56,
          avg_speed: 24,
          start_latitude: 33.6326525,
          start_longitude: -111.9791168,
          start_landmark_id: 972034,
          start_landmark_name: "Loading Station 2",
          end_latitude: 33.6327105,
          end_longitude: -111.9792261,
          end_landmark_id: 972034,
          end_landmark_name: "Loading Station 2"
        }
      ]
    }
