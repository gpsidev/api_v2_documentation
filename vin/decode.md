Example Request:

https://api.gpsinsight.com/v2/vin/decode?session_token=xxxx&vin=1N4AL21E67N48XXXX

Example Response:

    {
      head: { .... },
      data: {
        10111: {
          body: "SEDAN 4-DR",
          driveline: "front-wheel drive",
          engine: "2.5L L4 DOHC 16V",
          id: "10111",
          make: "Nissan",
          model: "Altima",
          trim: "2.5",
          year: "2007"
        }, { ... }
      }
    }
