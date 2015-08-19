Example Request: https://api.gpsinsight.com/v2/garmin/listcannedmessages?session_token=xxxx

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
        },
        {
          type: "Message",
          message: "Off Duty",
          message_id: "501517",
          garmin_message_id: "513",
          seq: "19",
          created: "6/23/13 5:32:14 PM"
        }
      ]
    }
