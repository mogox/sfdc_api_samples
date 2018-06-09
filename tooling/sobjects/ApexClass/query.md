# Sample Description
Simple request of an ApexClass record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, Name, Body, FullName, Metadata from ApexClass where Id = '{ID}'
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{ }
```

## request description
Query request for the ApexClass record.

## response
```json
{
  "size" : 1,
  "totalSize" : 1,
  "done" : true,
  "queryLocator" : null,
  "entityTypeName" : "ApexClass",
  "records" : [ {
    "attributes" : {
      "type" : "ApexClass",
      "url" : "/services/data/{version}/tooling/sobjects/ApexClass/{ID}"
    },
    "Id" : "{ID}",
    "Name" : "ApiatoApexTestClass",
    "Body" : "public with sharing class ApiatoApexTestClass {}",
    "FullName" : "ApiatoApexTestClass",
    "Metadata" : {
      "apiVersion" : 39.0,
      "packageVersions" : [ ],
      "status" : "Active",
      "urls" : null
    }
  } ]
}
```
