Description and examples for /v2/heartbeat/beat to follow...
The //beat// method is the simplest of messages.  It simply provides a heartbeat message for you to test our service with.  You can use this as a first step toward testing integration or as an uptime test on our servers.  An authorized session_token is not required.
  * Example:
    * http://api.gpsinsight.com/v2/heartbeat/beat
  * Response:

    {
    head: { ... },
    data: "beat"
    }
