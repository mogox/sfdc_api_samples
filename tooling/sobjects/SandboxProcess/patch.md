# Sample Description
PATCH Request for SandboxProcess

## PATH
```
/services/data/{version}/tooling/sobjects/SandboxProcess/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "RefreshAction": "ACTIVATE"
}
```

## request description
You can only do PATCH to Activate or Discard a sandbox once the status of SandboxProcess is Pending Activation.

## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
