Example Request:

https://api.gpsinsight.com/v2/fuelcard/listunassignedvehicles?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          vin: "CA454204XXXX",
          vehicle: "Truck 129",
          gpsi_vehicle_id: 700014XXXX
        }, { ... }
      ]
    }
