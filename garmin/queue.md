Show only the queued (unsent) dispatch/messages.  These messages are still on an internal queue to be sent.  They have not been received by the destination Garmin.

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
