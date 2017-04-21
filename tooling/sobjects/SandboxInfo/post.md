# Sample Description
POST Request for SandboxInfo

## PATH
```
/services/data/v39.0/tooling/sobjects/SandboxInfo
```
## Supported Versions
39.0

## request description
This will set the sandbox in a queue process, the sandbox will not be available until processing is complete. Use SandboxProcess to monitor progress of the sandbox process.

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
## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
