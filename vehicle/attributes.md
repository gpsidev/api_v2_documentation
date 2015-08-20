Example Request:

https://api.gpsinsight.com/v2/vehicle/attributes?session_token=xxxx&vehicle=Truck%20129

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009036",
          label: "Kristin PNP-3000V",
          attribute: {
            Color of Vehicle: "green"
          },
          category: {
            Delivery Zone: [
              "Zone 1",
              "Zone 2"
            ]
          }
        }
      ]
    }
