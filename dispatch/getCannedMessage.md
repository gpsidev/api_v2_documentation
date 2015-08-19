Example Request: https://api.gpsinsight.com/v2/dispatch/getcannedmessage?session_token=xxxx&message_id=294

Example Response:

    {
      head: { .... },
      data: [
        {
          type: "Status",
          message: "Start of Day",
          message_id: "294",
          garmin_message_id: "100",
          seq: "1",
          created: "5/26/11 9:40:45 AM"
        }
      ]
    }
