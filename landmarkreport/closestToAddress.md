Example Request:

https://api.gpsinsight.com/v2/landmarkreport/closesttoaddress?session_token=xxxx&address=7201%20E%20Henkel%20Way%20Scottsdale%20AZ&group=Landmarks%20by%20Adam&radius=10000

Example Response:

    {
      "head": { ... },
      "data": [
        {
          "id": 1005032,
          "label": "Whole Foods",
          "latitude": 33.6540995,
          "longitude": -111.9268682,
          "radius": 387,
          "polygon": "-111.9274557,33.6548226,0 -111.9259,33.654791,0 -111.9260824,33.6533828,0 -111.9264793,33.6533765,0 -111.9276863,33.6534523,0 -111.9278365,33.6540459,0 -111.9274288,33.6541974,0 -111.9274557,33.6548226,0",
          "color": "0000ff",
          "city": " ",
          "state": " ",
          "address": "7999 E. Whisper Rock Trail, Scottsdale, Arizona  85262",
          "geoc_lat": 33.6540996,
          "geoc_lng": -111.9268683,
          "min_lng": -111.9278365,
          "max_lng": -111.9259,
          "min_lat": 33.6533765,
          "max_lat": 33.6548226,
          "numericDistance": 0.386,
          "formattedDistance": "0.4 mi.",
          "numericDriveDistance": 0.765,
          "formattedDriveDistance": "0.8 mi.",
          "numericDriveTime": 2,
          "formattedDriveTime": "2 min"
        },
        {
          "id": 1002381,
          "label": "Verde Apartments",
          "latitude": 33.6498106,
          "longitude": -111.9352797,
          "radius": 391,
          "polygon": "-111.9342256,33.6488773,0 -111.9342577,33.6502884,0 -111.9358027,33.6502884,0 -111.9363016,33.6493328,0 -111.9342256,33.6488773,0",
          "color": "0000ff",
          "city": "Phoenix",
          "state": "AZ",
          "address": "17950 North 68th Street",
          "geoc_lat": 33.6495828,
          "geoc_lng": -111.9352636,
          "min_lng": -111.9363016,
          "max_lng": -111.9342256,
          "min_lat": 33.6488773,
          "max_lat": 33.6502884,
          "numericDistance": 0.907,
          "formattedDistance": "0.9 mi.",
          "numericDriveDistance": 1.416,
          "formattedDriveDistance": "1.4 mi.",
          "numericDriveTime": 4,
          "formattedDriveTime": "4 min"
        }
      ]
    }
