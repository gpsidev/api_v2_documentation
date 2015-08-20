Example Request:

https://api.gpsinsight.com/v2/landmark/create?session_token=xxxx&landmark=Dispatch%20Center%20D&latitude=33.58214&longitude=-111.92544&radius=750&radius_units=f

Example Response:

    {
      head: { .... },
      data: [
        {
          driver_id: "988009",
          result: "landmark created"
      ]
    }
