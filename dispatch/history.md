Example Request: https://api.gpsinsight.com/v2/dispatch/history?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          vin: "CA433208XXXX",
          vehicle: "Truck 190",
          queue_id: "5911904",
          table_id: "5884355",
          garmin_table: "sent",
          source: "CA",
          lmu_serial: "433107XXXX",
          position: "0",
          num_tries: "0",
          message_type: "Message",
          mesg_text: "Need backup to finish this job. Head this way when you're done with your delivery.",
          status: "Queued",
          created_dt: "2015/01/06 21:44:47:000",
          username: "klisson"
        }
      ]
    }
