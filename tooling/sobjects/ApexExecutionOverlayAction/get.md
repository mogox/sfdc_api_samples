# Sample Description
Simple request of an ApexExecutionOverlayAction record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexExecutionOverlayAction/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{}
```

## response
```json
{
  "ActionScriptType": "None",
  "CreatedById": "{UserId}",
  "CreatedDate": "2017-03-28T05:32:37.000+0000",
  "ExecutableEntityId": "{ApeClassOrApexTriggerId}",
  "ExpirationDate": "2020-03-29T04:43:12.000+0000",
  "Id": "{ID}",
  "IsDeleted": false,
  "IsDumpingHeap": true,
  "Iteration": 0,
  "LastModifiedById": "{UserId}",
  "LastModifiedDate": "2017-03-28T05:32:37.000+0000",
  "Line": 2,
  "ScopeId": "{UserId}",
  "SystemModstamp": "2017-03-28T05:32:37.000+0000",
  "attributes": {
    "type": "ApexExecutionOverlayAction",
    "url": "/services/data/{version}/tooling/sobjects/ApexExecutionOverlayAction/{ID}"
  }
}
```
