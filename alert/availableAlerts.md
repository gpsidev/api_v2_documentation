Example Request:

https://api.gpsinsight.com/v2/alert/availableAlerts?session_token=xxxx

Example Response:

    {
        head: { .... },
        data: [
            "accel": {
                "label": "Accel Alert",
                "desc": "Alert when a vehicle violates the specified accel threshold."
            },
            "assetin": {
                "label": "Asset Inputs Alert",
                "desc": "Alert when an asset's input changes status."
            }
        ] 
    }
