Example Request:

https://api.gpsinsight.com/v2/attribute/create?session_token=your_token

```json
{
	"attribute" : {
		"ca_name": "Test",
		"allow_multiple": false,
		"values": [1,3,4,5],
		"types": [1,8],
		"value_type_id": 3,
		"visible_to_use": true,
		"visible_to_edit": true
	}
}
```

Example Response:
```json 
{
    "head": { .... },
    "data": {
            "success": 1,
            "attribute": {
                "ca_name": "Test",
                "username": "gpsiautotest",
                "values": [1,3,4,5],
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
    
