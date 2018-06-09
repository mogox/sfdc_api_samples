# Sample Description
POST Request for TraceFlag

## PATH
```
/services/data/{version}/tooling/sobjects/TraceFlag
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{
  "ApexCode": "FINEST",
  "ApexProfiling": "FINEST",
  "Callout": "FINEST",
  "Database": "FINEST",
  "DebugLevelId": "{DebugLevelID}",
  "StartDate": "2018-02-22T06:45:00.000+0000",
  "System": "FINE",
  "TracedEntityId": "{ApexClassID,UserID or ApexTriggerID}",
  "Validation": "INFO",
  "Visualforce": "FINER",
  "Workflow": "FINER",
  "LogType": "USER_DEBUG",
  "ExpirationDate": "2018-02-23T06:35:00.000+0000"
}
```

## request description
Create a new TraceFlag record with FINEST logging level and expires in less than 24 hours.

## response
```json
{
  "id": "{ID}",
  "success": true,
  "errors": [],
  "warnings": []
}
```
