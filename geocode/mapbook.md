Description and examples for /v2/geocode/mapbook to follow...
Mapbook request from address or location (limited availability)

  * Example:
    * http://api.gpsinsight.com/v2/geocode/mapbook?&address=X
    * http://api.gpsinsight.com/v2/geocode/mapbook?latitude=X&longitude=X
  * Response:
  
    {
    head: { ... },
    data: [ 
      "Thomas Guide Phoenix: page 744, row 2, col D",
      "Yellow 1 Phoenix: page 152, row LV, col 190"
    ]
