Example Request:

https://api.gpsinsight.com/v2/landmark/read?session_token=xxxx&group=Dispatch%20Center%20B

Example Response:

    {
      head: { .... },
      data: [
        {
          id: 910481,
          label: "Dispatch Center B",
          latitude: 33.4344859,
          longitude: -112.1299026,
          radius: 750,
          color: "0000ff"
        }, { ... }
      ]
    }
