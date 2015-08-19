Example Request:

https://api.gpsinsight.com/v2/device/list?session_token=xxxx

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
        }, { ... }
      ]
    }
