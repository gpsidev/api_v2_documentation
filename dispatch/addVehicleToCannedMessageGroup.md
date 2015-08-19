Example Request:

https://api.gpsinsight.com/v2/dispatch/addvehicletocannedmessagegroup?session_token=xxxx&group=500233&vehicle=CA4332095511

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4332095511",
          result: "Created"
        }
      ]
    }
