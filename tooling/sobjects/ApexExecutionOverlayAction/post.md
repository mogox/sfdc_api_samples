# Sample Description
POST request of an ApexEmailNotification record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexEmailNotification/
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "ActionScriptType": "None",
  "ExecutableEntityId": "{ApeClassOrApexTriggerId}",
  "ExpirationDate": "2020-03-29T04:43:12.000+0000",
  "IsDumpingHeap": true,
  "Iteration": 1,
  "Line": 2,
  "ScopeId": "{UserId}"
}
```

## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
