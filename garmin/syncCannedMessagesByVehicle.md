Description and examples for /v2/garmin/syncCannedMessagesByVehicle to follow...
Sync the canned messages for the vehicle(s) specified.  
  * Example: 
    * http://api.gpsinsight.com/v2/garmin/syncCannedMessagesByVehicle?&token=authToken&vehicles[]=X&id_type=X
  * Response:

    {
    head: { ... },
    data: [
    [{
        vehicle: "Test Switch - JP",
        result: "Queued for Sync"
    ]}
    ]
