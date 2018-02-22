# Sample Description
POST Request for DebugLevel

## PATH
```
/services/data/v42.0/tooling/sobjects/DebugLevel
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{
  "DeveloperName": "{Custom_Name}",
  "Language": "en_US",
  "MasterLabel": "{Custom_Name}",
  "Workflow": "FINER",
  "Validation": "INFO",
  "Callout": "FINEST",
  "ApexCode": "FINEST",
  "ApexProfiling": "FINEST",
  "Visualforce": "FINER",
  "System": "FINE",
  "Database": "FINEST",
  "Wave": null
}
```

## request description
Create a new DebugLevel record.

## response
```json
{
  "id": "{ID}",
  "success": true,
  "errors": [],
  "warnings": []
}
```