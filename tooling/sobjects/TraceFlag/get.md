# Sample Description
Simple request of an TraceFlag Get

## PATH
```
/services/data/{version}/tooling/sobjects/TraceFlag/{ID}
```

## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
 {}
```

## request description
Get details for a specific TraceFlag record.

## response
```json
{
  "attributes": {
    "type": "TraceFlag",
    "url": "/services/data/{version}/tooling/sobjects/TraceFlag/{ID}"
  },
  "Id": "{ID}",
  "IsDeleted": false,
  "CreatedDate": "2018-02-22T22:16:33.000+0000",
  "CreatedById": "{UserID}",
  "LastModifiedDate": "2018-02-22T22:16:33.000+0000",
  "LastModifiedById": "{UserID}",
  "SystemModstamp": "2018-02-22T22:16:33.000+0000",
  "TracedEntityId": "{ApexClassID,UserID or ApexTriggerID}",
  "ExpirationDate": "2018-02-23T06:35:00.000+0000",
  "Workflow": "FINER",
  "Validation": "INFO",
  "Callout": "FINEST",
  "ApexCode": "FINEST",
  "ApexProfiling": "FINEST",
  "Visualforce": "FINER",
  "System": "FINE",
  "Database": "FINEST",
  "DebugLevelId": "{DebugLevelID}",
  "LogType": "USER_DEBUG",
  "StartDate": "2018-02-22T06:45:00.000+0000",
  "Wave": "INFO"
}
```
