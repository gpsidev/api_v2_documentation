Note: Queued (unsent) dispatch/messages are still on an internal queue to be sent. They have not been received by the destination Garmin.

Example Request:

https://api.gpsinsight.com/v2/garmin/queue?session_token=xxxx&vehicle=CA4332083727&group=Garbage%20Trucks

Example Response:

    {
    head: { ... },
    data: [
    {   vehicle: "Test Garmin",
        serial_number: 2937972834,
        nuvi_serial: 359234798,
        username: "tester",
        type: "Message",
        message: "Please restock your supplies before you go home",
        status: "Queued",
        position: 1
    }, { ... }
    ]}
