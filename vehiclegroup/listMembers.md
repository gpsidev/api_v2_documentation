Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/listmembers?session_token=xxxx&vehicle_group=Delivery

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA454204XXXX",
          vin: "1G1JC52462745XXXX",
          label: "Truck 130",
          serial_number: 454204XXXX
        }, { ... }
      ]
    }
