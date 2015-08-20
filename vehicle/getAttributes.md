Example Request:

https://api.gpsinsight.com/v2/vehicle/getattributes?session_token=xxxx&vehicle=CA4531009036

Example Response:

    {
      head: { .... },
      data: [
        {
          attribute_id: 2027584,
          id: "CA4531009036",
          input_type: "checkbox",
          key: "Delivery Zone",
          key_id: 314,
          label: "Truck 149",
          value: "Zone 2"
        }, { ... }
      ]
    }
