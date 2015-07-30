Description and examples for /v2/geocode/address to follow...
Geocode from an address 
  * Example:
    * http://api.gpsinsight.com/v2/geocode/address?&address=X
  * Response:
  
    {
    head: { ... },
    data: {
        latitude: "33.6589820",
        longitude: "-111.9256610",
        address: {
                houseNumber: "19001",
                street: "North Scottsdale Road",
                city: "Scottsdale",
                stateProvince: "AZ",
                postalCode: "85255",
                country: "US"
        
    }}
