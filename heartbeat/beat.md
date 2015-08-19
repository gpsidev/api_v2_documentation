Note: This method simply provides a heartbeat message with which to test our service. You can use this as a first step toward testing integration or as an uptime test on our servers. An authorized session_token is not required.

Example Request:

https://api.gpsinsight.com/v2/heartbeat/beat

Example Response:

    {
      head: { .... },
      data: "beat"
    }
