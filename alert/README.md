The `alert` endpoint allows users to define and update alerts coming from GPS Insight.
Alerts are based on defined conditions we check for on all incoming data, as it is received from tracking devices.
Alerts are sent to users via emails, text messages, and web service push messages.

The alerts as defined in this API have a lot of variables. This guide is to help you make sense of the common patterns.
Look at the guide on individual endpoints for parameter descriptions and examples.

### Working with Alerts
There are a few endpoints on this API that help you navigate that have already been configured on your account. 
* **/v2/alert/list** will list all the alerts configured by your username.
* **/v2/alert/history** will show a recent history of alert messages delivered for each alert configuration.
* **/v2/alert/read** will list details of a single alert. Look it up by its `alert_id`. 

### Alert Types
The GPS Insight portal application provides many different alert types. 
Each alert type has a keyword-name and there are two endpoints defined (`create` and `update`) to deal with each one.  
For example, the`Ignition` alert will notify users when a vehicle starts or stops. 
The two endpoints for the ignition alert are `createIgnition` and `updateIgnition`.
Here is a partial list of the endpoints that are or will included in the API. 
Check the endpoint documentation for current status of inclusion.
* **Ignition** alerts when a vehicle starts or stops
* **Stop/Idle** alerts when a vehicle stops or idles for a defined threshold in minutes
* **Speeding** alerts when a vehicle exceeds a static speed threshold (i.e. 85mph)
* **Posted** alerts when a vehicle exceeds a threshold above posted speed (i.e. 15mph over)

### Parameter Help
Let's look at parameters in logical groups, according to function, 
in case the endpoint documentation that groups them together is confusing.

#### Basic fields
All alerts have a description, and an on/off switch.
* **instance_description** 
* **active** 

#### Addressee fields
These fields will specify how the alert is sent to recipients and/or drivers.
* **addresses** 
* **alert_driver** 
* **alert_driver_msg** 
* **in_cab** 
* **in_cab_value** 

#### Vehicle Selection fields
Use these fields to specify a data source for your alerts. 
* **vehicle** 
* **vehicle_group** 
* **tree** 
* **node** 
* **alert_depth** 

#### Landmark fields
Almost all alerts have the ability to filter by inclusion or exclusion in a landmark.
* **landmark** 
* **landmark_group** 
* **landmark_proximity** 

#### Date-Range fields
Almost all alerts have the ability to filter by weekday hours or weekend odd-hours windows, 
including which days constitute weekdays and weekends. 
* **week_days** 
* **weekday_hour_end** 
* **weekday_hour_start** 
* **weekend_days** 
* **weekend_hour_start** 
* **weekend_hour_end** 

#### Frequency/Delay fields
Use these fields to control the number of alerts you receive. 
* **one_time** 
* **repeat_delay** 
* **per_vehicle_delay** 

