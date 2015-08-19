Example Request:

https://api.gpsinsight.com/v2/fuelcard/listunassigned?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          vin: "5JMJJ3J51AEXXXX",
          company_vehicle: "NAV2",
          license_state: "AZ",
          department: "ADMIN",
          card_id: 5XXX,
          description: "BLACK NAVIGATOR",
          source: "WEX"
        }, { ... }
      ]
    }
