Description and examples for /v2/garmin/addMessageToCannedMessageGroup to follow...
Add a message to a Canned Message group.  When doing this, your message will need to be the same type as the message group.
  * Example: 
    * http://api.gpsinsight.com/v2/garmin/addMessageToCannedMessageGroup?&token=authToken&message_id=X&group=X
  * Response:

    {
    head: { ... },
    data: [
    {   result: "Created" 
    }
    ]}
