# Sample Description
Simple GET of an ApexDebuggerSession record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexDebuggerSession/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{ }
```

## request description
GET request for a specific ApexDebuggerSession record.

## response
```json
{
  "attributes": {
    "type": "ApexDebuggerSession",
    "url": "/services/data/{version}/tooling/sobjects/ApexDebuggerSession/{ID}"
  },
  "Id": "{ID}",
  "IsDeleted": false,
  "Name": "Sample_Name",
  "CreatedDate": "2018-03-06T02:54:39.000+0000",
  "CreatedById": "{UserID}",
  "LastModifiedDate": "2018-03-06T02:56:42.000+0000",
  "LastModifiedById": "{UserID}",
  "SystemModstamp": "2018-03-06T02:56:42.000+0000",
  "IsInternal": false,
  "IsAsyncIgnored": false,
  "Status": "Detach",
  "StatusUsername": null,
  "StatusMessage": null,
  "StatusBy": "OrgAdmin",
  "UserIdFilter": "{UserID}",
  "RequestTypeFilter": null,
  "EntryPointFilter": null,
  "LicenseOrg": "{OrgID}",
  "License": "{LicenseID}",
  "LicenseType": "Scratch"
}
```
