Example Request:

https://api.gpsinsight.com/v2/landmarkgrouop/list?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          id: 3536,
          landmark_group: "Warehouses",
          owner: "tgypsy",
          master_group: 0,
          perm_rename: 1,
          perm_regroup: 1,
          perm_reshare: 1,
          member_count: 134
        }, { ... }
      ]
    }
