Example Request:

https://api.gpsinsight.com/v2/vehicle/distance?session_token=xxxx&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA453100XXXX",
          vin: "5FNRL38487803XXXX",
          label: "Truck 140",
          serial_number: 453100XXXX,
          start_fix_time: "Aug 1 2015 15:20:07",
          start_latitude: 33.6234518,
          start_longitude: -111.9244935,
          start_odometer: 57170.1,
          end_fix_time: "Aug 1 2015 15:33:03",
          end_latitude: 33.6327105,
          end_longitude: -111.9792261,
          end_odometer: 57173.7,
          distance: 3.6
        }
      ]
    }
