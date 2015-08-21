Note: The group must use a group id (label not supported).

Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/maintenance?session_token=xxxx&group=1015581

Example Response:

    {
      head: { .... },
      data: [
      {
        label: "Truck 240",
        vehicle: "CA423101XXX",
        maint_alert_id: 21064,
        value_offset: 5000,
        next_svc_value: 43918,
        offset_hrs: 0,
        maint_label: "Rotate Tires",
        updated_dt: "Aug 6 2013 10:45AM",
        svc_type: "m",
        pct: -5.74,
        runtime_hours: 2796.2,
        runtime_base: 0,
        odometer: 72602.1
      }, { ... }
      ]
    }
