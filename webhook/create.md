Example Request:

https://api.gpsinsight.com/v2/webhook/create?session_token=xxxx&url=https://xyzdev.demo&email=development@xyz.demo&towing_alert&type=location

Example Response:

    {
      head: { .... },
      data: {
          registered: true,
          id: 2718,
          error: ""
      }
    }
