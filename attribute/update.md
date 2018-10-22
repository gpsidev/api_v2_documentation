Example Request:

https://api.gpsinsight.com/v2/attribute/update?attr_id=1500409&session_token=your_token

```json
{
	"attribute" : {
		"ca_name": "Test1",
		"allow_multiple": 0,
		"values": [1,3,4],
		"types": [1,8],
		"value_type_id": 3,
		"visible_to_use": 1,
		"visible_to_edit": 1
	}
}
```

Example Success Response:

```json 
{
    "head": {...},
    "data": {
        "success": 1,
        "attribute": {
            "ca_name": "Test1",
            "username": "gpsiautotest",
            "values": [1,2,3],
            "ca_value_type_id": 3,
            "ca_entity_bm": 9,
            "cat_ordinality": 1,
            "trip_bm": 0,
            "perm_bm": 3,
            "ca_id": 1500409
        }
    }
}
```

