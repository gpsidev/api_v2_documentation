NOTE: Excluding the `vehicle` paramter will return all vehicles in the account.

Example Request (no detail):

https://api.gpsinsight.com/v2/vehicle/list?session_token=xxxx

Example Response (no detail):

    {
      "head": { .... },
      "data": [
        {
          "id": "CA454204XXXX",
          "vin": "1G1JC52462745XXXX",
          "label": "Truck 130",
          "serial_number": 454204XXXX
        }, { ... }
      ]
    }

Example Request (all details):

https://api.gpsinsight.com/v2/vehicle/list?session_token=xxxx&details=1

Example Response (all details):

    {
      head: { .... },
      data: [
        {
          "id": "CA4572257709",
          "vin": "123456ABCD7890EFG",
          "label": "2279-02",
          "serial_number": 4572257709,
          "source": "CA",
          "pnd": 4,
          "report_interval": 120,
          "runtime_base": 595.6,
          "idle_gph": 0.31,
          "install_dt": "2022-10-12 12:06:28",
          "fuel_type": "U",
          "country": "US",
          "license_state": "AZ",
          "license_number": "REA6BNA",
          "color": "Silver",
          "make": "Honda",
          "model": "Accord",
          "model_year": 2006,
          "odometer": 184101,
          "ref_id": "G-123",
          "phone_number": "3857751945",
          "email_address": "roshire@gmail.com",
          "alert_email": 0,
          "alert_sms": 0,
          "alert_garmin": 0,
          "alert_pref": 0
        }, { ... }
      ]
    }

Example Request (list detail columns):

https://api.gpsinsight.com/v2/vehicle/list?session_token=xxxx&details=license_state,license_number

Example Response (list detail columns):

    {
      head: { .... },
      data: [
        {
          "id": "CA4572257709",
          "vin": "123456ABCD7890EFG",
          "label": "2279-02",
          "serial_number": 4572257709,
          "license_state": "AZ",
          "license_number": "REA6BNA"
        }, { ... }
      ]
    }

