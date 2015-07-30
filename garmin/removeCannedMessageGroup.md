Description and examples for /v2/garmin/removeCannedMessageGroup to follow...
Remove a canned message group by group id.
  * Example: 
    * http://api.gpsinsight.com/v2/garmin/removeCannedMessageGroup?&token=authToken&group=X
  * Response:

    {
    head: { ... },
    data: [
    {   result: "Deleted"
    }
    ]}
