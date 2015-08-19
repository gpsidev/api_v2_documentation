Example Request: https://api.gpsinsight.com/v2/customersite/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "gpsi558d977cb4915",
          name: "Delivery Trucks",
          vehicle_group_count: 1
        },
        {
          id: "gpsi5592c5afdda20",
          name: "Snow Plows",
          vehicle_group_count: 1
        }
      ]
    }
