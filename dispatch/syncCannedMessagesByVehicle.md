Example Request: https://api.gpsinsight.com/v2/dispatch/syncCannedMessagesByVehicle?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        [{
            vehicle: "Truck 190",
            result: "Queued for Sync"
        ]}
     ]
    }
