The `route` endpoint allows users to do route processing.

There is a special route format used in the calls. It is a json string that defines the route.

	{
		"stops": [
			{"address": "1313 Disneyland Dr, Anaheim, CA 92802"},
			{"landmark_id": 810763},
			{"name": "test 1", "lat": 33.6590744, "lng":-111.9237522},
			{"address":"--this is an invalid address--"},
			{"address":"2200 West Coast Hwy, Newport Beach, CA 92663"}
		]
	}


Here is an example of how to optimize a route with the stops.

    https://api.gpsinsight.com/v2/route/optimize?route_json=ROUTE_JSON_STRING&token=YOUR_TOKEN


The ROUTE_JSON_STRING would be the same version as above, just all on one line

	{"stops":[{"address":"1313 Disneyland Dr, Anaheim, CA 92802"},{"landmark_id":810763},{"name":"test 1","lat":33.6590744,"lng":-111.9237522},{"address":"--this is an invalid address--"},{"address":"2200 West Coast Hwy, Newport Beach, CA 92663"}]}

and then url encoded


	%7B%22stops%22%3A%5B%7B%22address%22%3A%221313%20Disneyland%20Dr%2C%20Anaheim%2C%20CA%2092802%22%7D%2C%7B%22landmark_id%22%3A810763%7D%2C%7B%22name%22%3A%22test%201%22%2C%22lat%22%3A33.6590744%2C%22lng%22%3A-111.9237522%7D%2C%7B%22address%22%3A%22--this%20is%20an%20invalid%20address--%22%7D%2C%7B%22address%22%3A%222200%20West%20Coast%20Hwy%2C%20Newport%20Beach%2C%20CA%2092663%22%7D%5D%7D

making the full url look something like

    https://api.gpsinsight.com/v2/route/optimize?route_json=%7B%22stops%22%3A%5B%7B%22address%22%3A%221313%20Disneyland%20Dr%2C%20Anaheim%2C%20CA%2092802%22%7D%2C%7B%22landmark_id%22%3A810763%7D%2C%7B%22name%22%3A%22test%201%22%2C%22lat%22%3A33.6590744%2C%22lng%22%3A-111.9237522%7D%2C%7B%22address%22%3A%22--this%20is%20an%20invalid%20address--%22%7D%2C%7B%22address%22%3A%222200%20West%20Coast%20Hwy%2C%20Newport%20Beach%2C%20CA%2092663%22%7D%5D%7D&token=YOUR_TOKEN

The route optimizer with keep the first location and last location in the same position, and optimize the stops in between.

Here is the example return value of the `optimize` call

	{
		"head": {
			"status": "OK",
			"method": "optimize",
			"context": "customer",
			"request_time": "Mar 22 2016 16:14:27",
			"session_start": "Mar 22 2016 16:14:19",
			"request_count": 13,
			"request_ip": "12.39.158.227",
			"timer": 1.1448
		},
		"data": {
			"stops": [
				{
					"address": "1313 Disneyland Dr, Anaheim, CA 92802",
					"name": "1313 Disneyland Drive, Anaheim, California 92802",
					"lat": 33.8153022,
					"lng": -117.9261865
				},
				{
					"name": "test 1",
					"lat": 33.6590744,
					"lng": -111.9237522
				},
				{
					"landmark_id": 810763,
					"name": "AA drew test",
					"lat": 33.455505,
					"lng": -111.7620278
				},
				{
					"address": "2200 West Coast Hwy, Newport Beach, CA 92663",
					"name": "2200 West Coast Highway, Newport Beach, California 92663",
					"lat": 33.6186738,
					"lng": -117.9196782
				}
			],
			"errors": [
				{
					"address": "--this is an invalid address--"
				}
			]
		}
	}
