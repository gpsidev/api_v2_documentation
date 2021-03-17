Example Request:

https://api.gpsinsight.com/v2/hierarchy/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          label: "Company Vehicles",
          tree_id: 1500413,
          node_id: 1
        },
        {
          label: "Function",
          tree_id: 1500446,
          node_id: 1
        },
        { ... }
      ]
    }
