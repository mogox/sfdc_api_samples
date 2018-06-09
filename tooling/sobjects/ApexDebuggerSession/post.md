# Sample Description
Simple POST of an ApexDebuggerSession record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexDebuggerSession
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{
  "StatusUsername": null,
  "StatusMessage": null,
  "UserIdFilter": "{UserID}",
  "LicenseOrg": "{OrgID}",
  "LicenseType": "Scratch"
}
```

## request description
Create a ApexDebuggerSession record.

## response
```json
{
  "id": "{ID}",
  "success": true,
  "errors": [],
  "warnings": []
}
```
