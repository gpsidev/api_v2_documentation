The `CustomerSite` API is a collection of endpoints that allow you to manage your Customer Sites.
A Customer Site is a public map showing the current location of one or more of your vehicles, 
which you link to or embed in your own website, that does not require authentication to view. 

With Customer Sites, you can share the location of specific vehicles with customers right from your website.
For example, a trolley company may want to show the current location of their trolleys on their website.
The trolley company can create a Customer Site for each trolley, or all of them, and then embed the map on their website.

### Adding Vehicles
Once you have created a Customer Site, you can add vehicles to it by vehicle group. On the portal or through the API, 
create a vehicle group and assign the vehicles you want to share to that group. 
Then, use the `addVehicle` endpoint to add the vehicle group to the Customer Site.

### Map Link
To view your Customer Sites map, use this URL pattern with your Customer Sites ID as the `key` parameter:

```
https://portal.gpsinsight.com/d/publicmap.php?key=gpsi0000000000000&follow=true
```

The following are map options you can use by appending them to the URL as query parameters, such as `&follow=true` in the example above:

* **Follow** - Re-center the map on all shown vehicles as the map refreshes (example: `&follow=true`)
* **Landmark Alert** - Show an extra alert when vehicles enter or exit landmarks (example: `&alertlandmarks=true`)
* **Show Trails** - Hide the historical trail of the vehicle(s) on the map (example: `&showTrails=true`)
* **Trail Option** - Hide the option in the vehicle list to choose a different length trail (example: `&trailsoption=false`)
* **Trail Duration** - Specify the number of minutes of trail to show on the map. Use `-1` for 1 day. (example: `&trail_minutes=90`)
* **Static Map** - Disable zooming and panning on the map, so the user can't move the map. (example: `static=true`)
  This option requires a landmark group.  A static map will lock to the selected landmark group.  A use case for this is to see vehicles passing in and out of a work site (a landmark).

You can link directly to this URL for a full-screen view of the map, use that same link in an iFrame on your website,

### Embedding the Map
Alternately, you can use embed code pattern, with your Customer Sites ID as the `data-key` parameter, to embed the map right into your HTML. 

```html    
<!doctype html>
<div data-api-host="api.gpsinsight.com" data-trail-minutes="60" data-list-closed="false" data-trails="false" data-url-base="https://portal.gpsinsight.com" data-key="gpsi0000000000000" style="width:800px;height:600px;" id="cust-site-map-canvas" data-google-api-key=""></div>
<img src="https://portal.gpsinsight.com/common/images/map/loader.png" onload="var custSiteScript = document.createElement('script'); var custSiteNoCache = (new Date()).getTime(); custSiteScript.src = 'https://portal.gpsinsight.com/common/js/user/customersites.js?v=' + custSiteNoCache; document.body.appendChild(custSiteScript)" id="cust-site-script-img">
```

The following are map options you can use by adding key/value pairs to the embed code, such as `data-trails="false"` in the example above:

* **Follow** - Follow the vehicle(s) on the map (example: `data-follow="true"`)
* **Show Trails** - Show the trail of the vehicle(s) on the map (example: `data-trails="true"`)
* **Trail Duration** - Specify the number of minutes of trail to show on the map. Use `-1` for 1 day. (example: `data-trail-minutes=90`)
* **Hide Vehicle List** - Hide the vehicle list on the map (example: `data-list-closed=true`)
* **Show Address Bar** - Show the address bar in the map's browser window (example: `data-address-box`)
