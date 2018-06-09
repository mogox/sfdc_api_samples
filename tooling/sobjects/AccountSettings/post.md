# Sample Description
POST Request for AccountSettings

## PATH
```
/services/data/{version}/tooling/sobjects/AccountSettings
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "Metadata" : {
    "enableAccountOwnerReport" : null,
    "enableAccountTeams" : false,
    "showViewHierarchyLink" : true,
    "urls" : null
  },
  "FullName" : "Account2"
}
```
## response
```json
{
  "success" : true,
  "errors" : [ ]
}
```
