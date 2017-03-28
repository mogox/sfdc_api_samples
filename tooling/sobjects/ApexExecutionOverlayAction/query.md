# Sample Descriptiod
Simple request of an ApexExecutionOverlayAction record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, ScopeId, IsDumpingHeap, ActionScriptType, ExecutableEntityId, Line, Iteration, ExpirationDate, ActionScript from ApexExecutionOverlayAction where Id = '{Id}'
```
## Supported Versions
39.0

## request
 ```json
 {}
```

## response
```json
{
  "done": true,
  "entityTypeName": "ApexExecutionOverlayAction",
  "queryLocator": null,
  "records": [
    {
      "ActionScript": "System.debug('Apiato Test');",
      "ActionScriptType": "Apex",
      "ExecutableEntityId": "{ApeClassOrApexTriggerId}",
      "ExpirationDate": "2020-03-29T04:43:12.000+0000",
      "Id": "{ID}",
      "IsDumpingHeap": true,
      "Iteration": 1,
      "Line": 4,
      "ScopeId": "{UserID}",
      "attributes": {
        "type": "ApexExecutionOverlayAction",
        "url": "/services/data/v39.0/tooling/sobjects/ApexExecutionOverlayAction/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
