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
            P0491: {
              mld: "Secondary Air Injection System (Bank 1)",
              alt: " ",
              last: 1438476844,
              first: 1438436449,
              last_odo: -1,
              first_odo: -1,
              count: 5
            },
            P0492: {
              mld: "Secondary Air Injection System (Bank 2)",
              alt: " ",
              last: 1438476844,
              first: 1438436449,
              last_odo: -1,
              first_odo: -1,
              count: 5
            }
          }
        }
      ]
    }
