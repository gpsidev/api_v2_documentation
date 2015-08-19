Example Request: https://api.gpsinsight.com/v2/drivergroup/listmembers?session_token=xxxx&group=Delivery

Example Response:

    {
      head: { .... },
      data: [
        {
          id: 4550001,
          firstname: "John",
          lastname: "Jimplan",
          email: "john.jimplan@xyz.demo",
          phone: "5558168881"
        },
        {
          id: 4551423,
          firstname: "Tom",
          lastname: "Gypsy",
          email: "tgypsy@xyz.demo",
          phone: "5553153843"
        }
      ]
    }
