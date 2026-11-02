Example Request:

https://api.gpsinsight.com/v2/landmark/list?session_token=xxxx&group=Dispatch%20Centers

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

Example request with detailed information: 

http://api.gpsinsight.com/v2/landmark/list?detailed=location,address&landmark=119101

Example Response:

    {
      "head": {
        "status": "OK",
        "method": "listall",
        "context": "customer",
        "landmark_id": 119101,
        ...
      },
      "data": [
        {
          "id": 119101,
          "label": "7-Eleven Cooper",
          "latitude": 33.3494233,
          "longitude": -111.8064713,
          "radius": 171,
          "polygon": 1,
          "color": "0000ff",
          "owner": "grant",
          "can_edit": 1,
          "coordinates": "-111.8068233,33.3497362,0 -111.8061286,33.3497384,0 -111.8061018,33.3490708,0 -111.8064585,33.3490685,0 -111.8066463,33.3491335,0 -111.806885,33.3493419,0 -111.8068233,33.3497362,0",
          "min_lng": -111.806885,
          "max_lng": -111.8061018,
          "min_lat": 33.3490685,
          "max_lat": 33.3497384,
          "city": "GILBERT",
          "state": "AZ",
          "country": "85233",
          "address": "773 W ELLIOT RD",
          "geoc_lat": 33.34955,
          "geoc_lng": -111.80644
        }
      ]
    }