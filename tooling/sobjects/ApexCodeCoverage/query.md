# Sample Description
Simple request of an ApexCodeCoverage record

## PATH
```
/services/data/{version}/tooling/query?q=Select Id, ApexClassOrTriggerId, TestMethodName, ApexTestClassId, Coverage from ApexCodeCoverage where ApexClassOrTriggerId = '{ApexClassOrTriggerId}'
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

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
      "url" : "/services/data/{version}/tooling/sobjects/ApexCodeCoverage/{ID}"
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
