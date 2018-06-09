# Sample Description
Simple request of an DebugLevel record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, IsDeleted, DeveloperName, Language, MasterLabel, CreatedDate, CreatedById, LastModifiedDate, LastModifiedById, SystemModstamp, Workflow, Validation, Callout, ApexCode, ApexProfiling, Visualforce, System, Database, Wave from DebugLevel
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Query for all existing DebugLevel records.

## response
```json
{
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "DebugLevel",
  "records": [
    {
      "attributes": {
        "type": "DebugLevel",
        "url": "/services/data/{version}/tooling/sobjects/DebugLevel/{ID}"
      },
      "Id": "{ID}",
      "IsDeleted": false,
      "DeveloperName": "{Custom_Name}",
      "Language": "en_US",
      "MasterLabel": "{Custom_Name}",
      "CreatedDate": "2016-09-16T00:17:46.000+0000",
      "CreatedById": "{UserID}",
      "LastModifiedDate": "2016-09-16T00:17:46.000+0000",
      "LastModifiedById": "{UserID}",
      "SystemModstamp": "2016-09-16T00:17:46.000+0000",
      "Workflow": "INFO",
      "Validation": "INFO",
      "Callout": "INFO",
      "ApexCode": "DEBUG",
      "ApexProfiling": "INFO",
      "Visualforce": "INFO",
      "System": "DEBUG",
      "Database": "INFO",
      "Wave": null
    }
  ]
}
```
