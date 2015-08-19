Example Request: https://api.gpsinsight.com/v2/driver/getattributes?session_token=xxxx&driver=4551485

Example Response:

    {
      head: { .... },
      data: [
        {
          attribute_id: 2027661,
          firstname: "Tom",
          id: 4551485,
          input_type: "checkbox",
          key: "CDL Endorsement",
          key_id: 311,
          lastname: "Gypsy",
          value: "A"
        },
        {
          attribute_id: 2027663,
          firstname: "Tom",
          id: 4551485,
          input_type: "radio",
          key: "Hazmat Certified",
          key_id: 408,
          lastname: "Gypsy",
          value: "Yes"
        }
      ]
    }
