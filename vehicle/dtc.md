Example Request:

https://api.gpsinsight.com/v2/vehicle/dtc?session_token=xxxx&vehicle=Truck150&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          vin: "5TDXK3DC4DS35XXXX",
          label: "Truck150",
          serial_number: 453100XXXX,
          driver_id: 45520XX,
          first_name: "Justin",
          last_name: "Johnson",
          ref_id: "JaJ",
          dtc: {
            P0345: {
                mld: "Camshaft Position Sensor B - Bank 1 Circuit Malfunction",
                alt: "Engine may not be consuming fuel efficiently",
                last: "2015-09-29T12:29:32-07:00",
                first: "2015-09-23T17:58:36-07:00",
                count: 17
            },
            P0349: {
              mld: "Camshaft Position Sensor A Circuit Intermittent (Bank 2)",
              alt: "Vehicle is reporting a potential powertrain sensor malfunction",
              last: 2015-09-29T12:29:32-07:00,
              first: 2015-09-23T17:58:36-07:00,
              count: 5
            }
          }
        }
      ]
    }
