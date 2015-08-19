Example Request: https://api.gpsinsight.com/v2/garmin/getcannedmessagegroup?session_token=xxxx&group=191

Example Response:

    {
      head: { .... },
      data: [
        {
          type: "Response",
          group: "191",
          name: "Overtime",
          vehicle_count: "0",
          messages: [
            [
              {
                type: "Response",
                message: "Yes",
                message_id: "297",
                garmin_message_id: "100",
                seq: "1",
                created: "5/26/11 10:06:48 AM"
              }
            ],
            [
              {
                type: "Response",
                message: "No",
                message_id: "298",
                garmin_message_id: "200",
                seq: "2",
                created: "5/26/11 10:06:56 AM"
              }
            ],
          ],
          vehicles: "Array"
        }
      ]
    }
