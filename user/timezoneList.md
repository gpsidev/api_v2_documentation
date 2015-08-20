Note: The list of timezones can vary by user/account. The logged in user represents that user for which the session_token was obtained.

Example Request:

https://api.gpsinsight.com/v2/user/timezonelist?session_token=xxxx

Example Response:

    {
      head: { .... },
      data: [
        {
          tz_id: 1,
          country: "us",
          name: "US/Arizona",
          display_code: "MST",
          display_string: "-0700",
          offset: -25200,
          username: "mjones",
          user_country: "US"
        }, { ... }
      ]
    }
