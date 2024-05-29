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


* **Acceleration** Alert when a vehicle violates the specified acceleration threshold
* **Asset Input** Alert when an asset's input changes status 
* **Deceleration** Alert when a vehicle violates the specified deceleration threshold
* **Device Plugin** Alert when a driver hasn't plugged in their device after a threshold of being assigned to a vehicle
* **Diagnostic** Alert when a diagnostic threshold is reached
* **Driver Assign** Alert when a driver is assigned to a vehicle 
* **Driver Login** Alert when a driver does not log in when starting a trip 
* **DTC** Alert on Diagnostic Trouble Codes (supported devices only)
* **DVIR** Alert when a Driver Vehicle Inspection Report (DVIR) with Defects is received 
* **DVIR Status** Alert when a vehicle is moving without a DVIR completed or marked unsafe 
* **First Movement Reverse** Alert when the first device event movement is in reverse
* **Heartbeat** Alert when Garmin messages reach a specified queue depth 
* **HOS** Alert when specified Hours of Service (HOS) limit is reached 
* **HOS Driver Assign** Alert when a vehicle moves without HOS driver assigned 
* **Idle Time** Alert when a vehicle idles more than the specified limit
* **Ignition** Alert when a vehicle turns on or off
* **Inputs** Alert when an input changes status
* **Jamming** Alert when a supported GPS device detects Radio or GPS Jamming
* **Landmark** Alert as soon as a vehicle enters or exits a landmark (geofence)
* **Odd-Hours** Alert on movement within an odd-hours violation window
* **Out-Of-Range** Alert on vehicles that have not reported for a time
* **Posted Speed** Alert on vehicles violating posted speed limits (i.e. 15mph over)
* **Seat Belt Use** Alert when a vehicle exceeds the speed threshold while the seat belt is unbuckled 
* **Service Reminder** Alert when scheduled service is close or overdue
* **Speeding** Alert when a vehicle violates the specified speed limit (i.e. 85mph)
* **Stop/Idle** Alert on a stop or idle longer than a specified duration
* **Switch** Alert on device switches (supported devices) (i.e. Panic Switch, Power Cycle)PTO, Boom engaged, etc.) 
* **Towing** Alert when vehicle moves when ignition is off

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

