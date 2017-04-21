# Sample Description
Simple request of an SandboxInfo record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, SandboxName, LicenseType, AutoActivate, CopyChatter, CreatedDate, Description, HistoryDays, OnDemandRefresh from SandboxInfo where Id = '{ID}'
```
## Supported Versions
39.0

## request
 ```json
 { }
```

## request description
Query request for a SandboxInfo record. You can query for all the sandboxes by removing the where clause on this sample.

## response
```json
{
  "done": true,
  "entityTypeName": "SandboxInfo",
  "queryLocator": null,
  "records": [
    {
      "AutoActivate": false,
      "CopyChatter": false,
      "CreatedDate": "2015-10-17T15:39:37.000+0000",
      "Description": "Developer Sandbox, refreshed 7/30/2016",
      "HistoryDays": 30,
      "Id": "{ID}",
      "LicenseType": "DEVELOPER",
      "OnDemandRefresh": false,
      "SandboxName": "sbox",
      "attributes": {
        "type": "SandboxInfo",
        "url": "/services/data/v39.0/tooling/sobjects/SandboxInfo/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
