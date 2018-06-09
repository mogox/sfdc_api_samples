# Sample Description
POST Request for SandboxInfo

## PATH
```
/services/data/{version}/tooling/sobjects/SandboxInfo
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "AutoActivate": false,
  "CopyChatter": false,
  "Description": "Developer Sandbox created via Apiato.",
  "LicenseType": "DEVELOPER",
  "OnDemandRefresh": false,
  "SandboxName": "apiato"
}
```

## request description
This will set the sandbox in a queue process, the sandbox will not be available until processing is complete. Use SandboxProcess to monitor progress of the sandbox process.

## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
