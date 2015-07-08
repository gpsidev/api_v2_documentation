When retrieving a single canned message, you can do so by either specifying the message_id, or by specifying both the message type and sequence.

Example Response: 

    {
    head: { ... },
    data: [
    {   type: "Message",
        message: "Test Message2",
        message_id: 502997,
        garmin_message_id: 54500,
        seq: 578,
        created: "6/24/14 8:30:30 AM" 
    }
    ]}
