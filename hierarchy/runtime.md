Example Request:

https://api.gpsinsight.com/v2/hierarchy/runtime?session_token=xxxx&tree=division&date=03/18/2021

Example Response:

    {
      head: { .... },
      data: [
         {
            "id": "CA4641092866",
            "vin": "JTLZE4FEXFJ071247",
            "label": "8000-01",
            "serial_number": 4641092866,
            "age_minutes": 704,
            "fix_time": "03/19/2021 03:37:52",
            "runtime_desc": "Total GPS Device Hours",
            "odometer": 59411.4,
            "runtime_hours": "1640.192",
            "runtime_lifetime": "1640.192",
            "runtime_lifetime_hours": "1640.192",
            "source": "summary"
         },{ ... }
      ]
    }