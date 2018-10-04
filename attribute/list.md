Example Request:

https://api.gpsinsight.com/v2/attribute/list?page=1&page_size=1&session_token=your_token

Example Response:

    {
      head: { .... },
      data: {
        "paginator": {
          "basis": 2,
          "page": "2",
          "page_size": "3",
          "page_count": 1
        },
        data: [
          {
            "ca_id": 1500383,
            "ca_name": "Boom Height",
            "vehicles": true,
            "landmarks": true
          },
          {
            "ca_id": 1500384,
            "ca_name": "Email Distributions",
            "users": true,
            "drivers": true,
            "vehicles": true,
            "landmarks": true
          }, { ... }
         ]
      }
    }
