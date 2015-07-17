Description and examples for /v2/garmin/removeVehicleFromCannedMessageGroup to follow...
Remove a vehicle from a Canned Message Group.  This can be done by vehicle name, vin, lmu_serial, or nuvi_serial.
  * Example: 
    * http://api.gpsinsight.com/v2/garmin/removeVehicleFromCannedMessageGroup?&token=authToken&group=X&vehicle=x
    * http://api.gpsinsight.com/v2/garmin/removeVehicleFromCannedMessageGroup?&token=authToken&group=X&vin=x
    * http://api.gpsinsight.com/v2/garmin/removeVehicleFromCannedMessageGroup?&token=authToken&group=X&lmu_serial=x
    * http://api.gpsinsight.com/v2/garmin/removeVehicleFromCannedMessageGroup?&token=authToken&group=X&nuvi_serial=x
  * Response:

    {
    head: { ... },
    data: [
    {   result: "Deleted" 
    }
    ]}
