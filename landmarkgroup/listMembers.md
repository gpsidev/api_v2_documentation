Example Request:

https://api.gpsinsight.com/v2/landmarkgroup/listmembers?session_token=xxxx&group=Dispatch%20Centers

Example Response:

    {
      head: { .... },
      data: [
        {
          id: 910480,
          label: "Dispatch Center A",
          latitude: 33.3501009,
          longitude: -111.7029156,
          radius: 750,
          polygon: 0,
          color: "0000ff",
          owner: "tgypsy"
        }, { ... }
      ]
    }
