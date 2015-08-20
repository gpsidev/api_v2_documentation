Example Request:

https://api.gpsinsight.com/v2/user/getpreference?session_token=xxxx&accountlevel=1

Example Response:

    {
      head: { .... },
      data: [
        {
          preference: "default_vehicle_group_id",
          value: "3838"
        }
      ]
    }
