**Provider API Homework**

**POST**

Request url: localhost:8080/provider

Request body: json format
```
{
    "provider" : {
        "first_name": "a",
        "last_name": "b",
        "middle_name": "c",
        "dob": "1990-01-01"
    }
}
```


**GET**

Request url: localhost:8080/provider 

Respond:
```
{
    "providerList": [
        {
            "firstName": "a",
            "lastName": "b",
            "middleName": "c",
            "dob": "1990-01-01"
        }
    ]
}
```


