# Sample Description
Simple request of an DebugLevel Get

## PATH
```
/services/data/v42.0/tooling/sobjects/DebugLevel/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
 { }
```

## request description
Get details for a specific DebugLevel record.

## response
```json
{
  "attributes": {
    "type": "DebugLevel",
    "url": "/services/data/v42.0/tooling/sobjects/DebugLevel/{ID}"
  },
  "Id": "{ID}",
  "IsDeleted": false,
  "DeveloperName": "{Custom_Name}",
  "Language": "en_US",
  "MasterLabel": "{Custom_Name}",
  "CreatedDate": "2016-09-16T00:17:34.000+0000",
  "CreatedById": "{UserID}",
  "LastModifiedDate": "2016-09-16T00:17:34.000+0000",
  "LastModifiedById": "{UserID}",
  "SystemModstamp": "2016-09-16T00:17:34.000+0000",
  "Workflow": "FINER",
  "Validation": "INFO",
  "Callout": "FINEST",
  "ApexCode": "FINEST",
  "ApexProfiling": "FINEST",
  "Visualforce": "FINER",
  "System": "FINE",
  "Database": "FINEST",
  "Wave": null
}
```
