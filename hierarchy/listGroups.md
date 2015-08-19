Example Request:

https://api.gpsinsight.com/v2/hierarchy/listgroups?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          edge: "2",
          edge_path: "G",
          groupId: 1011194,
          node: "West",
          node_depth: 1,
          node_id: 5,
          tree_id: 1500413,
          parent_node: 1
        }, { ... }
      ]
    }
