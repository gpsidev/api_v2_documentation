Example Request:

https://api.gpsinsight.com/v2/userauth/sendpasswordreset?session_token=xxxx&username=tgypsy&method=email

Example Response:

    {
      head: { .... },
      data: [
        {
          ret: "sent",
          username: "tgypsy"
        }
      ]
    }
