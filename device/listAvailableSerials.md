Example Request:

https://api.gpsinsight.com/v2/device/listavailableserials?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
            serial_number: 21435XXXX,
            type: "O",
            alternate_id: null,
            name: 21435XXXX
        }, { ... }
      ]
    }
