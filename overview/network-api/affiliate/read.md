# List Affiliate

| **HTTP method** | End Point |
| :--- | :--- |
| **GET** | **/affiliate** |
| GET | /affiliate |
| GET | /affiliate/{id} |

## **Response body parameters**

* _**Get all the affiliates**_

```bash
curl -X GET -H "X-Api-Key: {key}" -H "Cache-Control: no-cache" "http://api.vnative.com/affiliate"
```

```javascript
{
    "data": {
        "affiliates": [
            {
                "org_id": "string",
                "username": null,
                "name": "string",
                "email": "string",
                "password": "string (hashed)",
                "phone": "9958636988",
                "country": "IN",
                "currency": "USD",
                "type": "publisher",
                "login": null,
                "_id": "string (24 characters)",
                "live": false,
                "created": "2016-10-21",
                "modified": null,
                "meta": []
            },
            {
                "org_id": "string",
                "username": null,
                "name": "string",
                "email": "abc@example.com",
                "password": "string (hashed)",
                "phone": "string",
                "country": "IN",
                "currency": "USD",
                "type": "publisher",
                "login": null,
                "_id": "string (24 characters)",
                "live": true,
                "created": "2016-10-25",
                "modified": "2016-11-08",
                "meta": {
                    "afields": {
                        "skype_id": "live:testUser",
                        "screenshot": "image.png"
                    }
                }
            }
        ]
    }
}
```

* _**Get a single affiliate info**_

```bash
curl -X GET -H "X-Api-Key: {key}" -H "Cache-Control: no-cache" "http://api.vnative.com/affiliate/{id}"
```

```javascript
{
    "data": {
        "affiliate": {
            "org_id": "string",
            "username": null,
            "name": "string",
            "email": "faizan@cloudstuff.tech",
            "password": "03aa85cad0cd378e1ce36e0e12e34910b8e3b06f",
            "phone": "9958636988",
            "country": "IN",
            "currency": "USD",
            "type": "publisher",
            "login": null,
            "_id": "580a45201d41c82966347b8b",
            "live": false,
            "created": "2016-10-21",
            "modified": null,
            "meta": []
        }
    }
}
```

