# Sample Description
Simple request of an SandboxInfo Get

## PATH
```
/services/data/{version}/tooling/sobjects/SandboxInfo/{ID}
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
  "ApexClassId": null,
  "AutoActivate": false,
  "CopyChatter": false,
  "CreatedById": "{UserId}",
  "CreatedDate": "2015-10-17T15:39:37.000+0000",
  "Description": "Developer Sandbox, refreshed 7/30/2016",
  "HistoryDays": 30,
  "Id": "{ID}",
  "IsDeleted": false,
  "LastModifiedById": "{UserId}",
  "LastModifiedDate": "2015-10-17T15:39:37.000+0000",
  "LicenseType": "DEVELOPER",
  "OnDemandRefresh": false,
  "SandboxName": "sbox",
  "SystemModstamp": "2015-10-17T15:39:37.000+0000",
  "TemplateId": null,
  "attributes": {
    "type": "SandboxInfo",
    "url": "/services/data/{version}/tooling/sobjects/SandboxInfo/{ID}"
  }
}
```
