Example Request: https://api.gpsinsight.com/v2/device/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
            serial_number: 21419XXXX,
            alternate_id: null,
            type: "O",
            date_inventoried: "Oct 31 2014 12:50PM",
            date_registered: "Oct 31 2014 12:51PM",
            description: "GPS Insight",
            account_id: 90054,
            vehicle: "GTSolar3",
            vin: "OC21419XXXX"
        },
        {
          serial_number: 453100XXXX,
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
