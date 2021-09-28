Example Request(s):

https://api.gpsinsight.com/v2/vehicle/list?session_token=xxxx
https://api.gpsinsight.com/v2/vehicle/list?session_token=xxxx&detail=1

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA454204XXXX",
          vin: "1G1JC52462745XXXX",
          label: "Truck 130",
          serial_number: 454204XXXX
        },
        { ... }
      ]
    }
    
    
    {
      head: { .... },
      data: [
        {
          id: "CA454204XXXX",
          vin: "1G1JC52462745XXXX",
          label: "Truck 130",
          serial_number: 454204XXXX
          source: "CA",
          report_interval: 120,
          idle_gph: 0.421,
          install_dt: "Dec 23 2020 3:05PM",
          fuel_type: "U",
          country: "US",
          license_state: "MO",
          make: "Volkswagen",
          model: "Touareg",
          model_year: 2013,
          odometer: 85,
          alert_email: 0,
          alert_sms: 0,
          alert_garmin: 0,
          alert_pref: 0,
          serial_number_label: "4572256488"
        },
        { ... }
      ]
    }
