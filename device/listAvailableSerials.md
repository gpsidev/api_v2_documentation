Example Request: https://api.gpsinsight.com/v2/device/listavailableserials?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          serial_number: 2403408,
          type: "P",
          alternate_id: null,
          name: 2403408
        },
        {
          serial_number: 4531001290,
          type: "C",
          alternate_id: null,
          name: 4531001290
        },
      ]
    }
