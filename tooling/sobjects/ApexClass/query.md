# Sample Description
Simple request of an ApexClass record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, Name, Body, FullName, Metadata from ApexClass where Id = '{ID}'
```
## Supported Versions
38.0

## request
 ```json
 { }
```

## request description
Query request for the Apex Class record.  Find the ID

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
      "url" : "/services/data/v39.0/tooling/sobjects/ApexClass/{ID}"
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
