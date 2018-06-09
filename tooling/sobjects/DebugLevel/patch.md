# Sample Description
PATCH Request for DebugLevel

## PATH
```
/services/data/{version}/tooling/sobjects/DebugLevel/{ID}
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
  "Database": "FINE",
  "Wave": null
}
```

## request description
Update an existing DebugLevel record.

## response
```json
{}
```
