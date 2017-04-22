# Sample Description
PATCH Request for SandboxProcess

## PATH
```
/services/data/v39.0/tooling/sobjects/SandboxProcess/{ID}
```
## Supported Versions
39.0

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
