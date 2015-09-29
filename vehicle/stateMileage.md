Example Request:

https://api.gpsinsight.com/v2/vehicle/statemileage?session_token=xxxx&vehicle=Truck150&date=9/28/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531014796",
          vin: "39802939399999",
          label: "Truck150",
          state: "AZ",
          distance: 19.4,
          trip_start: "Sep 28 2015 12:36:34",
          trip_end: "Sep 28 2015 20:33:16",
          latitude_start: 33.586627,
          longitude_start: -111.8311138,
          latitude_end: 33.5866656,
          longitude_end: -111.8311746
        }
      ]
    }
