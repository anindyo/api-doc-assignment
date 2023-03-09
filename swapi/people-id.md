# GET /people/{id}

## Introduction

This request retrieves the list of a specific character of the Star Wars universe.

## Method

GET

## Base URL

https://swapi.py4e.com/api

## Resource

people

## Parameters

|Parameter|Type|Required?|Data type|Description|
|:--|:--|:--|:--|:--|
|id|Path|Y|string|The unique ID of a character.|

## Request URL

https://swapi.py4e.com/api/people/{id}

## Sample request URL

https://swapi.py4e.com/api/people/1

## Table of response parameters

|Parameter|Data type|Description|
|:--|:--|:--|
|name|string|Name of the character.|
|height|sring|Height of the character&mdash;expressed in centimeters.|
|mass|string|Weight of the character&mdash;expressed in kilograms.|
|hair_color|string|Hair color of the character.|
|skin_color|string|Skin color of the character.|
|eye_colot|string|Eye color of the character.|
|birth_year|string|Birth year of the character in the in-universe standard.|
|gender|string|Gender of the character.|
|homeworld|string|URL of the planet where the character resides.|
|films|array|An array of URLs of the films that featured the character.|
|species|array|An array of URLs of the species owned by the character.|
|vehicles|array|An array of URLs of the vehicles piloted by the character.|
|starships|array|An array of URLs of the starships piloted by the character.|
|created|string|The date when the character was created&mdash;expressed in the ISO 8601 format.|
|edited|string|The date when the character was edited&mdash;expressed in the ISO 8601 format.|
|url|string|URL of the character.|

## Sample response

```json
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "Luke Skywalker",
            "height": "172",
            "mass": "77",
            "hair_color": "blond",
            "skin_color": "fair",
            "eye_color": "blue",
            "birth_year": "19BBY",
            "gender": "male",
            "homeworld": "https://swapi.py4e.com/api/planets/1/",
            "films": [
                "https://swapi.py4e.com/api/films/1/",
                "https://swapi.py4e.com/api/films/2/",
                "https://swapi.py4e.com/api/films/3/",
                "https://swapi.py4e.com/api/films/6/",
                "https://swapi.py4e.com/api/films/7/"
            ],
            "species": [
                "https://swapi.py4e.com/api/species/1/"
            ],
            "vehicles": [
                "https://swapi.py4e.com/api/vehicles/14/",
                "https://swapi.py4e.com/api/vehicles/30/"
            ],
            "starships": [
                "https://swapi.py4e.com/api/starships/12/",
                "https://swapi.py4e.com/api/starships/22/"
            ],
            "created": "2014-12-09T13:50:51.644000Z",
            "edited": "2014-12-20T21:17:56.891000Z",
            "url": "https://swapi.py4e.com/api/people/1/"
        }
    ]
}
```

