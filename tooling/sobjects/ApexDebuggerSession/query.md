# Sample Description
Simple request of an ApexDebuggerSession record

## PATH
```
/services/data/v42.0/tooling/query/?q=Select Id, Name, Status, StatusUsername, StatusMessage, StatusBy, UserIdFilter, LicenseOrg, License, LicenseType, CreatedDate, LastModifiedDate from ApexDebuggerSession
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Query request for ApexDebuggerSession records.

## response
```json
{
  "size" : 1,
  "totalSize" : 1,
  "done" : true,
  "queryLocator" : null,
  "entityTypeName" : "ApexDebuggerSession",
  "records" : [ {
    "attributes" : {
      "type" : "ApexDebuggerSession",
      "url" : "/services/data/v42.0/tooling/sobjects/ApexDebuggerSession/{ID}"
    },
    "Id": "{ID}",
    "Name": "00000006",
    "CreatedDate": "2018-01-09T22:18:00.000+0000",
    "LastModifiedDate": "2018-01-09T22:18:01.000+0000",
    "Status": "Dead",
    "StatusUsername": null,
    "StatusMessage": "You exceeded your licensed number of debugging sessions. Please end other sessions or purchase more.",
    "StatusBy": "OrgAdmin",
    "UserIdFilter": "{UserIdFilterID}",
    "LicenseOrg": "000000000000000",
    "License": "000000000000000",
    "LicenseType": null
  } ]
}
```