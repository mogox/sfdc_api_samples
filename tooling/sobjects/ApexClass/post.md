# Sample Description
POST Request for ApexClass

## PATH
```
/services/data/{version}/tooling/sobjects/ApexClass
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "Name" : "ApexTestClass",
  "Body" : "public with sharing class ApexTestClass {}"
}

```

## request description
Create a new ApexClass record called ApexTestClass.

## response
```json
{
  "id" : "{ID}",
  "success" : true,
  "errors" : [ ]
}
```
