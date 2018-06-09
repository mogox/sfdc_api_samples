# Sample Description
Simple request of an ApexClass Get

## PATH
```
/services/data/{version}/tooling/sobjects/ApexClass/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
 { }
```

## request description
Get details for a specific ApexClass record.

## response
```json
{
  "attributes" : {
    "type" : "ApexClass",
    "url" : "/services/data/{version}/tooling/sobjects/ApexClass/{ID}"
  },
  "Id" : "{ID}",
  "NamespacePrefix" : null,
  "Name" : "ApexTestClass",
  "ApiVersion" : 42.0,
  "Status" : "Active",
  "IsValid" : true,
  "BodyCrc" : 3.646420087E9,
  "Body" : "public with sharing class ApexTestClass {}",
  "LengthWithoutComments" : 38,
  "CreatedDate" : "2017-01-31T22:44:34.000+0000",
  "CreatedById" : "00541000000uEgSAAU",
  "LastModifiedDate" : "2017-01-31T22:44:34.000+0000",
  "LastModifiedById" : "00541000000uEgSAAU",
  "SystemModstamp" : "2017-01-31T22:44:34.000+0000",
  "ManageableState" : "unmanaged",
  "SymbolTable" : {
    "constructors" : [ ],
    "externalReferences" : [ ],
    "id" : "{ID}",
    "innerClasses" : [ ],
    "interfaces" : [ ],
    "key" : "{ID}",
    "methods" : [ ],
    "name" : "ApexTestClass",
    "namespace" : null,
    "parentClass" : "",
    "properties" : [ ],
    "tableDeclaration" : {
      "annotations" : [ ],
      "location" : {
        "column" : 27,
        "line" : 1
      },
      "modifiers" : [ "public", "with sharing" ],
      "name" : "ApexTestClass",
      "references" : [ ],
      "type" : "ApexTestClass"
    },
    "variables" : [ ]
  },
  "Metadata" : {
    "apiVersion" : 42.0,
    "packageVersions" : [ ],
    "status" : "Active",
    "urls" : null
  },
  "FullName" : "ApexTestClass"
}
```
