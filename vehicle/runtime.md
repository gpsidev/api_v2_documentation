Example Request:

https://api.gpsinsight.com/v2/vehicle/runtime?session_token=xxxx&vehicle=CA4531009XXX&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          vin: "5FNRL38487803XXXX",
          label: "Truck 149",
          serial_number: 4531009036,
          age_minutes: 27364,
          fix_time: "8/1/15 15:33:03",
          runtime_desc: "Total GPS Device Hours",
          odometer: 57173.7,
          runtime_hours: "58.189",
          runtime_lifetime: 58.189,
          span: {
            run_days: 1,
            run_hours: "0.460",
            idle_hours: "0.179",
            miles_driven: "7.5"
            },
          source: "summary"
        }
      ]
    }
