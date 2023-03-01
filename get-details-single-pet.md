# Introduction

This request retrieves the details of a single pet.

# Method

GET

# Base URL

https://petstore3.swagger.io/api/v3

# Resource

pet

# Parameters

|Parameter|Type|Required?|Data type|Description|
|:--|:--|:--|:--|:--|
|petID|Path|Y|int64|The unique ID of a pet.|

# Sample request

> GET https://petstore3.swagger.io/api/v3/pet/5678

# Sample response

```json
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

```