# Sample Description
Simple request of an SandboxProcess Get

## PATH
```
/services/data/{version}/tooling/sobjects/SandboxProcess/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
 { }

```
## response
```json
{
  "ActivatedById": null,
  "ActivatedDate": null,
  "ApexClassId": null,
  "AutoActivate": false,
  "CopyChatter": false,
  "CopyProgress": 0,
  "CreatedById": "{UserId}",
  "CreatedDate": "2017-04-21T23:21:27.000+0000",
  "Description": "Developer Sandbox created via Apiato.",
  "EndDate": null,
  "HistoryDays": 0,
  "Id": "{ID}",
  "IsDeleted": false,
  "LastModifiedById": "{UserId}",
  "LastModifiedDate": "2017-04-21T23:21:27.000+0000",
  "LicenseType": "DEVELOPER",
  "OnDemandRefresh": false,
  "RefreshAction": null,
  "SandboxInfoId": "{SandboxInfoId}",
  "SandboxName": "apiato",
  "SandboxOrganization": null,
  "StartDate": "2017-04-21T23:21:27.000+0000",
  "Status": "Pending",
  "SystemModstamp": "2017-04-21T23:21:27.000+0000",
  "TemplateId": null,
  "attributes": {
    "type": "SandboxProcess",
    "url": "/services/data/{version}/tooling/sobjects/SandboxProcess/{ID}"
  }
}
```
