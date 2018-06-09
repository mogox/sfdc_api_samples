# Sample Description
Simple request of an AccountSettings Get

## PATH
```
/services/data/{version}/tooling/sobjects/AccountSettings/{DurableId}
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
 { }

```
## response
```json
{
  "attributes" : {
    "type" : "AccountSettings",
    "url" : "/services/data/{version}/tooling/sobjects/AccountSettings/{DurableId}"
  },
  "Id" : "000000000000000AAA",
  "DurableId" : "{DurableId}",
  "Metadata" : {
    "enableAccountOwnerReport" : null,
    "enableAccountTeams" : false,
    "showViewHierarchyLink" : true,
    "urls" : null
  },
  "FullName" : "Account",
  "IsAccountOwnerReportEnabled" : false,
  "IsAccountTeamsEnabled" : false,
  "ShowViewHierarchyLink" : true
}
```
