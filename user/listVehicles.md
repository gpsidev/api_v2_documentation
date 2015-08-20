Note: The current user represents the user for which the session_token was generated.

Example Request:

https://api.gpsinsight.com/v2/user/listvehicles?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA43321038XX",
          vin: "433210XXXX",
          label: " ",
          serial_number: 433210XXXX
        }, { ... }
      ]
    }
