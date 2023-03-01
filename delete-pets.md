# DELETE pet/{petID}

## Introduction

This request deletes the record of a specific pet.

## Method

DELETE

## Base URL

https://petstore3.swagger.io/api/v3

## Resource

pet

## Parameters

|Parameter|Type|Required?|Data type|Description|
|:--|:--|:--|:--|:--|
|petID|Path|Y|int64|The unique ID of a pet.|

## Sample request

> DELETE https://petstore3.swagger.io/api/v3/pet/5678

## Sample response

```bash
Pet deleted
```