Example Request:

https://api.gpsinsight.com/v2/channel/setcurrentversion?session_token=xxxx&channel=my_custom_app&date=20150727.

Example Response:

    {
    head: { ... },
    data: [
      {
        channel: "my_custom_app",
        version: "1.0",
        req_cnt: 1277,
        user_cnt: 99
      },
      {
        channel: "my_custom_app",
        version: "1.1",
        req_cnt: 14,
        user_cnt: 1
      }
    ]
    }
