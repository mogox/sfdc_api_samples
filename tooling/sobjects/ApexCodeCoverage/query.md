# Sample Description
Simple request of an ApexCodeCoverage record

## PATH
```
/services/data/v39.0/tooling/query?q=Select Id, ApexClassOrTriggerId, TestMethodName, ApexTestClassId, Coverage from ApexCodeCoverage where ApexClassOrTriggerId = '{ApexClassOrTriggerId}'
```
## Supported Versions
39.0

## request
 ```json
 { }
```

## response
```json
{
  "size" : 1,
  "totalSize" : 1,
  "done" : true,
  "queryLocator" : null,
  "entityTypeName" : "ApexCodeCoverage",
  "records" : [ {
    "attributes" : {
      "type" : "ApexCodeCoverage",
      "url" : "/services/data/v39.0/tooling/sobjects/ApexCodeCoverage/{ID}"
    },
    "Id" : "{ID}",
    "ApexClassOrTriggerId" : "{ApexClassOrTriggerId}",
    "TestMethodName" : "testApiatoTestClass",
    "ApexTestClassId" : "{ApexTestClassId}",
    "Coverage" : {
      "coveredLines" : [ 7, 12, 16],
      "uncoveredLines" : [ 9, 13, 17, 22]
    }
  } ]
}
```
