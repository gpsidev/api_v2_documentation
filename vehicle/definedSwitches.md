Example Request:

https://api.gpsinsight.com/v2/vehicle/definedswitches?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          id: 1683,
          label: "Buzzer",
          on_state: " ",
          off_state: " ",
          type: "output",
          features: "none",
          speed_threshold: 0
        }, { ... }
      ]
    }
