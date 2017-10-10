The `vehicle` endpoint allows users to get and modify information about 
vehicles in their fleet.

#### Vehicle Parameter

It is important to understand the flexibility we allow with the `vehicle` 
parameter in most of these endpoints. In some endpoints, the `id` value is 
returned, such as in /v2/vehicle/list. This is our primary key for vehicles
but is a value many outside customers are unfamiliar with. They would more 
likely be using one of several alternative ids for a vehicle, such as VIN, 
serial number, or vehicle label. 

Because of this, we allow you to use whatever ID you want, as long as it's 
unique.  And of the following can be used, and we will look up the ID. All 
are valid as long as a lookup finds a unique vehicle record.

1.   GPS Insight's ID (two letters, up to 12 numbers)
1.   The [standard VIN](https://en.wikipedia.org/wiki/Vehicle_identification_number) (17 characters)
1.   Device serial number
1.   Vehicle Name (configurable on your account)
1.   Partial vehicle name (must be unique) 
