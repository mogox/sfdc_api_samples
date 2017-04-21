# Sample Description
PATCH Request for SandboxInfo

## PATH
```
/services/data/v39.0/tooling/sobjects/SandboxInfo/{ID}
```
## Supported Versions
39.0

## request description
This will set the sandbox in a queue process and will have to wait until processing is complete to make further changes to it. Use SandboxProcess to monitor progress of the sandbox process.

## request
```json
{
  "AutoActivate": false,
  "CopyChatter": false,
  "Description": "Developer Sandbox patched via Apiato.",
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
