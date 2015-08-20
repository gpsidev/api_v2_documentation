Example Request:

https://api.gpsinsight.com/v2/hierarchynode/postedspeed?session_token=xxxx&tree=Division&node=Scottsdale&start=08/01/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA454204XXXX",
          vin: "KNMAT2MT8FP5XXXX",
          label: "Truck 230",
          age_minutes: 27223,
          fix_time_mst: "Aug 1 2015 12:09:55",
          latitude: 33.42268,
          longitude: -111.67814,
          heading: 94,
          ignition: "on",
          max_speed: 57,
          avg_speed: 14,
          inst_speed: 55,
          speed_limit: 45,
          odometer: 7187.3,
          driver_id: 4549XXX,
          first_name: "Jennifer",
          last_name: "Meyers",
          percent_over: 20,
          violation: 10
        }, { ... }
      ]
    }
