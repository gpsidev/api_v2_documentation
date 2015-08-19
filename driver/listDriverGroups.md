Example Request:

https://api.gpsinsight.com/v2/driver/listdrivergroups?session_token=xxxx&driver=Trent

Example Response:

    {
      head: { .... },
      data: [
        {
         group_id: 2,
         group: "ALL DRIVERS"
        },
        {
         group_id: 14,
         group: "Delivery"
        }, { ... }
      ]
    }
