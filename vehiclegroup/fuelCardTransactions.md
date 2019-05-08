Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/fuelCardTransactions?session_token=xxxx&group=ALL+VEHICLES&start_date=4/1/2019&end_date=4/2/2019

Example Response:

    {
      head: { .... },
      data: [
        {
          "vehicle_id": 99999,
          "vin": "CAXXXXXXXXXXX",
          "vin2": "12345678912345678",
          "vehicle_description": "Fast car",
          "vehicle": "Vehicle Label",
          "inserted_adj": "2017-07-28 09:22:01",
          "fuel_capacity": null,
          "transaction_utf": "May  1 2019 16:53:27",
          "transaction_adj": "2019-05-01 22:53:27",
          "gallons": 13.74,
          "gross_dollars": 39.83,
          "price_per_gallon": 2.899,
          "product_group": "Unleaded Regular",
          "odometer": 62000,
          "transaction_id": 2242424,
          "wex_site_id": "24242424",
          "site_id": 6346,
          "site_name": "Some Gas Station",
          "brand_name_fuel": "EXXON",
          "street_addr_1": "1400 E Le Fevre Rd, Sterling, IL 61081",
          "city": "Sterling Township",
          "state": "IL",
          "zip": "61081",
          "latitude": 41.801950,
          "longitude": -89.680985,
          "geoc_lat": null,
          "geoc_lng": null,
          "geoc_diff_miles": null,
          "query_window_start": "May  1 2019 10:53:27",
          "query_window_end": "May  1 2019 22:53:27",
          "fuel_cap_pct": null,
          "installed": 1,
          "fix_time_utf": "May  1 2019 10:20:00",
          "gps_latitude": 41.801950,
          "gps_longitude": -89.680985,
          "gps_odometer": 10018,
          "driver_id": 242424,
          "no_fix_time": 0,
          "gps_distance": 0,
          "time_diff": null,
          "card": "WEX",
          "card_name": "Owner of Fuel Card",
          "g_driver_id": 654654,
          "refid": null,
          "fname": "John",
          "lname": "Smith",
          "fuel_level_before": false,
          "fuel_level_after": false,
          "fix_time_adj": "2019-05-01 13:20:00",
          "fix_time_gmt": "2019-05-01T17:20:00+00:00"
        }
      ]
    }
