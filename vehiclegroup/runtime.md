Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/runtime?session_token=xxxx&vehicle_group=Delivery&start=8/1/2015&end=8/15/2015

Example Response:

    {
      head: { .... },
      data: [
      {
        id: "CA433210XXXX",
        vin: "43321038XX",
        label: "Truck 210",
        serial_number: 4332103XXX,
        age_minutes: 96502,
        fix_time: "6/15/15 10:40:07",
        runtime_desc: "Total GPS Device Hours",
        odometer: 100753.6,
        runtime_hours: "3528.482",
        runtime_lifetime: 3528.482,
        source: "summary"
      }, { ... }
      ]
    }
