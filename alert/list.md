Example Request:

https://api.gpsinsight.com/v2/alert/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          watcher_id: 1000,
          instance_description: "IDLE ALERT",
          active: 1,
          watcher_type: "idle"
        },
        {
          watcher_id: 1100,
          instance_description: "SPEEDING ALERT",
          active: 1,
          watcher_type: "speed"
        },
        {
          watcher_id: 1102,
          instance_description: "DELIVERY SIGNATURE ALERT",
          active: 0,
          watcher_type: "fence"
        }
      ]
    }
