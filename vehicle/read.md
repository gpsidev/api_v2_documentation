Example Request(s):

https://api.gpsinsight.com/v2/vehicle/read?session_token=xxxx&vehicle=CA454204XXXX
https://api.gpsinsight.com/v2/vehicle/read?session_token=xxxx&vehicle=Truck 130

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA454204XXXX",
          vin: "1G1JC52462745XXXX",
          label: "Truck 130",
          serial_number: 454204XXXX
        }
      ]
    }
