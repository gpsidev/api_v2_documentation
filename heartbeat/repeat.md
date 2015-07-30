Description and examples for /v2/heartbeat/repeat to follow...
The //repeat// method is the second simplest of messages.  It simply parrots a word back to the user in a formatted response.  Use this to test passing parameters into a method and reading the response.  An authorized session_token is not required.
  * Example:
    * http://api.gpsinsight.com/v2/heartbeat/repeat?word=bulbous%20bouffant
  * Response:

    {
    head: { ... },
    data: "bulbous bouffant"
    }
