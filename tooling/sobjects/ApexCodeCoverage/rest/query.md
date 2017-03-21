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
      "coveredLines" : [ 7, 12, 16, 20, 72 ],
      "uncoveredLines" : [ 9, 13, 17, 22, 23, 26, 27, 30, 31, 34, 36, 37, 42, 46, 47, 48, 49, 50, 52, 57, 61, 62, 63, 66, 67, 73, 74, 76, 77, 78 ]
    }
  } ]
}
```
