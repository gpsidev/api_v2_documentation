Example Request: https://api.gpsinsight.com/v2/garmin/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          cap_id: "609",
          nuvi_serial: "385442XXXX",
          source: "CA",
          lmu_serial: "4332083996",
          vehicle: "Truck 190",
          vin: "CA433208XXXX",
          vin2: "1GNSCHE00BR37XXXX",
          fname: "April",
          lname: "Smith"
        },
        {
          source: "CA",
          lmu_serial: "464116XXXX",
          vehicle: "Truck 208",
          vin: "CA4641163952",
          vin2: "CA464116XXXX"
        }
      ]
    }
