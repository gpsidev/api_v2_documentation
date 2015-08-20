Example Request:

https://api.gpsinsight.com/v2/hierarchynode/list?session_token=xxxx&node=NE&tree=Division

Example Response:

    {
      head: { .... },
      data: 
        {
          13: {
            id: 13,
            label: "NE",
            vehicles: [
              "CA4641147754"
            ]
          }
        }, { ... }
    }
