# Sample Description
Simple request of an AccountSetting record

## PATH
```
/services/data/{version}/tooling/query?q=Select DurableId from AccountSettings
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
  "size" : 1,
  "totalSize" : 1,
  "done" : true,
  "queryLocator" : null,
  "entityTypeName" : "AccountSettings",
  "records" : [ {
    "attributes" : {
      "type" : "AccountSettings",
      "url" : "/services/data/{version}/tooling/sobjects/AccountSettings/{DurableId}"
    },
    "DurableId" : "{DurableId}"
  } ]
}
```
