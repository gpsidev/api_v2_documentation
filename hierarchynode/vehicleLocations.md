Example Request:

https://api.gpsinsight.com/v2/hierarchynode/vehiclelocations?session_token=xxxx&node=NE&tree=Division

Example Response:

    {
      head: { .... },
      data: {
            8: {
              id: 8,
              label: "Scottsdale",
              vehicles: [
                {
                  id: "CA4331022808",
                  vin: "UNKNOWN",
                  serial_number: 433102XXXX,
                  vehicle: "Truck 206",
                  ageMinutes: 26612,
                  lastPing: {
                  date: "08/01/2015",
                  time: "22:15:57"
                },
                lastReported: {
                  date: "08/01/2015",
                  time: "22:15:57"
                },
                ignition: "off",
                latitude: 33.75409,
                longitude: -111.93781,
                speed: 4,
                heading: 319
              }, { ... }
            ]
          }
      }
    }
