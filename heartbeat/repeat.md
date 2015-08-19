Note: This simple message parrots a word back to you in a formatted response. Use this method to test passing parameters into a method and reading the response. An authorized session_token is not required.

Example Request:

https://api.gpsinsight.com/v2/heartbeat/repeat?word=bulbous%20bouffant

Example Response:

    {
      head: { .... },
      data: "bulbous bouffant"
    }
