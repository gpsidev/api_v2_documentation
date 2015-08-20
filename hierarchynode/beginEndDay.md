Example Request:

https://api.gpsinsight.com/v2/hierarchynode/beginendday?session_token=xxxx&tree=Division&node=Scottsdale&start=08/01/2015&end=08/02/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA453100XXXX",
          vin: "5FNRL38437B40XXXX",
          label: "Truck 240",
          serial_number: 4531009052,
          odometer: 174903.5,
          driver_id: 1009582,
          first_name: "Tom",
          last_name: "Marks",
          trips: 10,
          date: "08/01/2015",
          start_time: "11:15:13",
          end_time: "22:44:09",
          duration: 41336,
          trip_duration: 6929,
          distance: 46.2,
          max_speed: 56,
          avg_speed: 20,
          start_latitude: 33.3469039,
          start_longitude: -111.7825039,
          end_latitude: 33.3468030,
          end_longitude: -111.7825038
        }, { ... }
      ]
    }
