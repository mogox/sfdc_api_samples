# Sample Description
Simple request of an ApexCodeCoverage Get

## PATH
```
/services/data/v39.0/tooling/sobjects/ApexCodeCoverage/{ID}
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
  "attributes" : {
    "type" : "ApexCodeCoverage",
    "url" : "/services/data/v39.0/tooling/sobjects/ApexCodeCoverage/{ID}"
  },
  "Id" : "{ID}",
  "IsDeleted" : false,
  "CreatedDate" : "2017-02-16T19:04:01.000+0000",
  "CreatedById" : "00541000000uEgSAAU",
  "LastModifiedDate" : "2017-02-16T19:04:01.000+0000",
  "LastModifiedById" : "00541000000uEgSAAU",
  "SystemModstamp" : "2017-02-16T19:04:01.000+0000",
  "ApexTestClassId" : "{ApexTestClassId}",
  "TestMethodName" : "testApiatoTestClass",
  "ApexClassOrTriggerId" : "{ApexClassOrTriggerId}",
  "NumLinesCovered" : 3,
  "NumLinesUncovered" : 4,
  "Coverage" : {
    "coveredLines" : [ 7, 12, 16],
    "uncoveredLines" : [ 9, 13, 17, 22]
  }
}
```
