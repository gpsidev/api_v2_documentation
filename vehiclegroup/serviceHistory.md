Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/servicehistory/xml?session_token=xxxx&group=Delivery&start=8/1/2013&end=8/2/2016

Example Response:

    {
      head: { .... },
      data: [{
        "id":"CA4332095511",
        "vin":"CA4332095511",
        "label":"John GTI",
        "serial_number":4332095511,
        "is_hours":0,
        "cost":65,
        "service_date":"Feb 20 2015 12:00AM",
        "notes":"Synthetic oil",
        "service_value":45042,
        "service_value_hours":0
      }]
}
