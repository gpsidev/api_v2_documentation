Note: Landmark must use id instead of label.

Example Request:

https://api.gpsinsight.com/v2/landmarkgroup/addlandmark?session_token=xxxx&landmark=099010&group=Dispatch%20Centers

Example Response:

    {
      head: { .... },
      data: "Added to Dispatch Centers"
    }

Note: The response lists the name of the landmark group listed in the request.
