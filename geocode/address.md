Example Request:

https://api.gpsinsight.com/v2/geocode/timezone?session_token=xxxx&address=7201%20E%20Henkel%20Way

Example Response:

{
    head: { .... },
    data: {
          latitude: "33.6590744",
          longitude: "-111.9237522",
          address: {
            houseNumber: "7201",
            street: "East Henkel Way",
            city: "Scottsdale",
            stateProvince: "AZ",
            postalCode: "85255",    
            country: "US"
          }
      }
}

