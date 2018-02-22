# Sample Description
Simple request of an TraceFlag record

## PATH
```
/services/data/v42.0/tooling/query/?q=Select Id, ApexCode, ApexProfiling, Callout, Database, DebugLevelId, StartDate, System, TracedEntityId, Validation, Visualforce, Workflow, LogType, ExpirationDate, CreatedDate from TraceFlag
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
 ```json
 { }
```

## request description
Query request for all existing TraceFlag records.

## response
```json
  {
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "TraceFlag",
  "records": [
    {
      "attributes": {
        "type": "TraceFlag",
        "url": "/services/data/v42.0/tooling/sobjects/TraceFlag/{ID}"
      },
      "Id": "{ID}",
      "ApexCode": "FINEST",
      "ApexProfiling": "FINEST",
      "Callout": "FINEST",
      "Database": "FINEST",
      "DebugLevelId": "{DebugLevelID}",
      "StartDate": "2017-03-28T06:45:00.000+0000",
      "System": "FINE",
      "TracedEntityId": "{EntityID}",
      "Validation": "INFO",
      "Visualforce": "FINER",
      "Workflow": "FINER",
      "LogType": "USER_DEBUG",
      "ExpirationDate": "2017-03-28T06:55:00.000+0000",
      "CreatedDate": "2017-03-28T01:46:50.000+0000"
    }
  ]
}
```