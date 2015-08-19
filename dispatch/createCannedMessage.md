Example Request: https://api.gpsinsight.com/v2/dispatch/createcannedmessage?session_token=xxxx&message=Lunch%20Break&type=Status

Example Response:

    {
      head: { .... },
      data: [
        {
          message_id: "1001863",
          result: "Created"
        }
      ]
    }
