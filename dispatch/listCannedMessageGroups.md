Example Request:

https://api.gpsinsight.com/v2/dispatch/listcannedmessagegroups?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          type: "Message",
          group: "10",
          name: "Mowing",
          vehicle_count: "1"
        },
        {
         type: "Response",
         group: "191",
         name: "Overtime",
         vehicle_count: "0"
        }
      ]
    }
