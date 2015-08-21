Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/read?session_token=xxxx&group=Delivery

Example Response:

    {
      head: { .... },
      data: [
        {
          group_id: 1012000,
          label: "Delivery",
          vehicle_count: 16
        }
      ]
    }
