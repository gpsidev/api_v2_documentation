Example Request:

https://api.gpsinsight.com/v2/hierarchynode/listnodes?session_token=xxxx&tree=Division&node=East

Example Response:

    {
      head: { .... },
      data: 
        {
          4: {
              id: 4,
              label: "East",
              nodes: {
                7: {
                  id: 7,
                  label: "Tempe",
                  nodes: {
                    13: {
                      id: 13,
                      label: "NE"
                    }
                }
              }
          }
      }
    }
