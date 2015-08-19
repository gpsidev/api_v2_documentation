Note: Your message must be the same type as the message group to which you're adding it.

Example Request: https://api.gpsinsight.com/v2/dispatch/addmessagetocannedmessagegroup?session_token=xxxx&group=500233&message_id=501547

Example Response:

    {
      head: { .... },
      data: [
        {
          message_id: "501647",
          result: "Created"
        }
      ]
    }
