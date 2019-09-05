Example Request:

https://api.gpsinsight.com/v2/drivergroup/getAttributes?session_token=xxxx&group=Service&username=ameyer

Example Response:

    {
      head: { .... },
      data: [
        {
            "attribute_id": 999999,
            "firstname": "Firstname",
            "id": 999999,
            "input_type": "checkbox",
            "key": "Attribute Name",
            "key_id": 311,
            "lastname": "Lastname",
            "value": "Attribute Value"
        }
      ]
    }
