Example Request:

https://api.gpsinsight.com/v2/userauth/passwordrules?session_token=xxxx

Example Response:

    {
    "head": { ... },
    "data": {
        "rules_text": "Password policy:\n6-60 length - letters, numbers, some special characters (!@$#-_)\n",
        "rules_regex": "/^(?=.*[a-z])(?=.*[A-Z])(?=.*\\d)(?=.*[^\\w\\d\\s]).{6,}$/"
        }
    }
