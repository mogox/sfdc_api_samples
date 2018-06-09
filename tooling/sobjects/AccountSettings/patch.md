# Sample Description
PATCH request of an AccountSettings record

## PATH
```
/services/data/{version}/tooling/sobjects/AccountSettings/{DurableID}
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "FullName": "Account",
  "Metadata": {
    "enableAccountOwnerReport": null,
    "enableAccountTeams": true,
    "showViewHierarchyLink": true,
    "urls": null
  }
}
```

## request description
This sample updates enableAccountTeams from being false to true.

## response
```json
{}
```
