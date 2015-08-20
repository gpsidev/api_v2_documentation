Example Request:

https://api.gpsinsight.com/v2/hierarchynode/beginendday?session_token=xxxx&tree=Division&node=Scottsdale

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
