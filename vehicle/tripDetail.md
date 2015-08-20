Example Request:

https://api.gpsinsight.com/v2/vehicle/tripdetail?session_token=xxxx&vehicle=CA4531009XXX&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          label: "Truck 149",
          serial_number: 453100XXXX,
          trip_type: "S",
          trip_start: "Jul 31 2015 19:15:14",
          rip_end: "Aug 1 2015 13:56:29",
          duration: 18.69,
          latitude_start: 33.632687,
          longitude_start: -111.9791251,
          latitude_end: 33.632687,
          longitude_end: -111.9791251,
          in_progress: 0
        }, { ... }
      ]
    }
