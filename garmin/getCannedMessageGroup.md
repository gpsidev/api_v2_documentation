Description and examples for /v2/garmin/getCannedMessageGroup to follow...
Get a Canned Message Group by group id.

  * Example: 
    * http://api.gpsinsight.com/v2/garmin/getCannedMessageGroup?&token=authToken&group=X
  * Response:

    {
    head: { ... },
    data: [
    {
        type: "Message",
        group: "1704",
        name: "Test Message Group",
        vehicle_count: "1",
        messages: [
            [{
                type: "Message",
                message: "Test Message2",
                message_id: 502997,
                garmin_message_id: 54500,
                seq: 578,
                created: "6/24/14 8:30:30 AM"
            }],
            [{
                type: "Message",
                message: "Test Message3",
                message_id: 502998,
                garmin_message_id: 54600,
                seq: 579,
                created: "6/24/14 10:20:47 AM"
            }],
        ],
        vehicles": [
            "Test Vehicle 1",
            "Test Vehicle 2",
        ]
    }
    ]}
