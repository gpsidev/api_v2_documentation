Example Request: https://api.gpsinsight.com/v2/dispatch/getreceivedcustomforms?session_token=xxxx&start=20150101

Example Response:

    {
      head: { .... },
      data: [
        {
          vehicle: "John GTI",
          vin: "CA433209XXXX",
          serial_number: "433209XXXX",
          nuvi_serial: "389481XXXX",
          submit_id: "5",
          title: "Equipment Work Order",
          sent: "4/30/15 2:50:00 PM",
          received: "04/30/2015 14:51:00",
          form_id: "91",
          form_version: "1",
          form_data: [
                    {
                      title: "Work Order #",
                      type: "alphanumeric",
                      value: "4883"
                    },
                    {
                      title: "Equipment Number",
                      type: "integer",
                      value: "22856"
                    },
                    {
                      title: "Location of Work Performed",
                      type: "alphanumeric",
                      value: "HCA"
                    },
                    {
                      title: "Make",
                      type: "alphanumeric",
                      value: "Cat"
                    },
                    {
                      title: "Model",
                      type: "alphanumeric",
                      value: "D8R"
                    },
                    {
                      title: "Hour Meter Reading",
                      type: "integer",
                      value: "6490"
                    }
                  ]
        }
      ]
    }
