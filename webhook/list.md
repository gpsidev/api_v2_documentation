Example Request:

https://api.gpsinsight.com/v2/webhook/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          name: "driver_assign_alert",
          email: "xyzdev@xyzcompany.demo",
          url: "https://xyzdev.com/server/callback_vehicle.php",
          socket_id: "",
          filter: "",
          type: "driver_assignment",
          username: "mjones",
          content_type: "form",
          account_id: 90054,
          outbound_queue_name: "90054:mjones",
          id: 2086,
          status: "running",
          total: 108,
          queue_depth: 0,
          custom_auth_header: null
        }
      ]
    }
