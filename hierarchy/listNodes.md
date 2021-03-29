Example Request:

https://api.gpsinsight.com/v2/hierarchy/listNodes?session_token=xxxxx&type=V&tree=Company%20Vehicles

Example Response:

    {
        "head": {....},
        "data": {
            "1": {
                "id": 1,
                "label": "Company Vehicles",
                "nodes": {
                    "3": {
                        "id": 3,
                        "label": "Installs"
                    },
                    "4": {
                        "id": 4,
                        "label": "Administration"
                    },
                    "5": {
                        "id": 5,
                        "label": "Sales",
                        "nodes": {
                            "10": {
                                "id": 10,
                                "label": "Inside Sales"
                            },
                        }
                    }
                }
            }
        }
    }
