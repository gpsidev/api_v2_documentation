Example Request:

https://api.gpsinsight.com/v2/vehicle/getdriverattributes?session_token=xxxx&vehicle=CA4531009036&driver=Kristin

Example Response:

    {
      head: { .... },
      data: [
        {
          attribute_id: 2027591,
          firstname: "Tom",
          id: 4551485,
          input_type: "checkbox",
          key: "CDL Endorsement",
          key_id: 311,
          lastname: "Gypsy",
          value: "N"
        }, { ... }
      ]
    }
