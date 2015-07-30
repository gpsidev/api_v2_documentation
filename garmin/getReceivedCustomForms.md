Description and examples for /v2/garmin/getReceivedCustomForms to follow...
Get Received Custom Forms, with optional filtering parameters. 
  * Example:
    * http://api.gpsinsight.com/v2/garmin/getreceivedcustomforms?group=X&vehicle=X&form=X&start=X&end=X
  * Response:

    {
    head: { ... },
    data: [
    {
        "vehicle": "Red Car - DG",
        "vin": "CA4641240198",
        "title": "Job Form",
        "form_id": 11,
        "form_version": 4,
        "sent": "01/06/2015 15:30:00",
        "received": "01/06/2015 15:30:00",
        "submit_id": 1,
        "form_data": [
        {
            "title": "Job Type",
            "value": "Pick Up"
        },
        {
            "title": "Weight of Load",
            "value": "2410"
        },
        {...},
        {...},
    ]},
    {...},
    {...}
    ]
