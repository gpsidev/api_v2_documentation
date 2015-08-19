Note: You can specify vehicle name, vin, lmu_serial, or nuvi_serial.

Example Request:

https://api.gpsinsight.com/v2/garmin/removevehiclefromcannedmessagegroup?session_token=xxxx&group=500233&vehicle=CA4332095511

Example Response:

    {
      head: { .... },
      data: [
        {
          result: "Deleted"
        }
      ]
    }
