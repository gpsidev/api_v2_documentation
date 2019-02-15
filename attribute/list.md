Example Request:

https://api.gpsinsight.com/v2/attribute/list?q=o&page=1&page_size=3&sort=-ca_name,vehicles&session_token=your_token

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
            "ca_id": 1500384,
            "ca_name": "Email Distributions",
            "value_type": "integer",
            "users": true,
            "vehicles": true,
            "drivers": true,
            "landmarks": true,
            "hierarchy": false
          },
          {
            "ca_id": 1500383,
            "ca_name": "Boom Height",
            "value_type": "emails",
            "users": false,
            "vehicles": true,
            "drivers": false,
            "landmarks": true,
            "hierarchy": false
          }, { ... }
         ]
      }
    }
