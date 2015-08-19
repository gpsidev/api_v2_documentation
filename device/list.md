Example Request: https://api.gpsinsight.com/v2/device/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          serial_number: 7528,
          alternate_id: null,
          type: "W",
          date_inventoried: "Oct 6 2010 7:36AM",
          date_registered: "Aug 17 2015 3:42PM",
          description: "GPS Insight",
          account_id: 90054,
          vehicle: "Test",
          vin: "FS75x8"
        },
        {
          serial_number: 4531009036,
          alternate_id: null,
          type: "C",
          date_inventoried: "May 20 2015 12:16PM",
          date_registered: "May 21 2015 10:23PM",
          description: "GPS Insight",
          account_id: 90054,
          vehicle: "Truck 150",
          vin: "CA453100XXXX"
        },
      ]
    }
