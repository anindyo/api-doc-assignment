# Introduction

This request retrieves the details of pets by status. 
# Method

GET

# Base URL

https://petstore3.swagger.io/api/v3

# Resource

pet/findByStatus

# Parameters

|Parameter|Type|Required?|Data type|Description|
|:--|:--|:--|:--|:--|
|status|Query|Y|string|Status of pets. Supported values: `available`, `sold`, and `pending`.|

# Sample request

> GET https://petstore3.swagger.io/api/v3/pet/findByStatus?status=available

# Sample response

```json
[
    {
        "id": 8,
        "category": {
            "id": 4,
            "name": "Lions"
        },
        "name": "Lion 2",
        "photoUrls": [
            "url1",
            "url2"
        ],
        "tags": [
            {
                "id": 1,
                "name": "tag2"
            },
            {
                "id": 2,
                "name": "tag3"
            }
        ],
        "status": "available"
    },
    {
        "id": 105,
        "category": {
            "id": 1,
            "name": "Dogs"
        },
        "name": "doggie",
        "photoUrls": [
            "string"
        ],
        "tags": [
            {
                "id": 0,
                "name": "string"
            }
        ],
        "status": "available"
    },
    {
        "id": 5678,
        "category": {
            "id": 3,
            "name": "Fish"
        },
        "name": "vikky",
        "photoUrls": [
            "string"
        ],
        "tags": [
            {
                "id": 0,
                "name": "string"
            }
        ],
        "status": "available"
    }
]
    
```