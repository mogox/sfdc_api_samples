# Sample Description
Simple request of an SandboxProcess record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, SandboxInfoId, SandboxName, SandboxOrganization, StartDate, Status, LicenseType from SandboxProcess where SandboxInfoId = '{SandboxInfoId}'
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
 { }
```

## request description
Query request to find the status of a sandbox after it is enqueued.

## response
```json
{
  "done": true,
  "entityTypeName": "SandboxProcess",
  "queryLocator": null,
  "records": [
    {
      "Id": "{ID}",
      "LicenseType": "DEVELOPER",
      "SandboxInfoId": "{SandboxInfoId}",
      "SandboxName": "apiato",
      "SandboxOrganization": null,
      "StartDate": "2017-04-21T23:21:27.000+0000",
      "Status": "Pending",
      "attributes": {
        "type": "SandboxProcess",
        "url": "/services/data/{version}/tooling/sobjects/SandboxProcess/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
