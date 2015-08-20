Example Request:

https://api.gpsinsight.com/v2/vehicle/getdriver?session_token=xxxx&vehicle=CA4531009036

Example Response:

    {
      head: { .... },
      data: [
        {
          id: 4551485,
          alert_pref: 3,
          email: "tom.gypsy@xyz.demo",
          firstname: "Tom",
          lastname: "Gypsy",
          phone: "5553153843"
        }, { ... }
      ]
    }
