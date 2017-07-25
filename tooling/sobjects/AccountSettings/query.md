# Sample Description
Simple request of an AccountSetting record

## PATH
```
/services/data/v40.0/tooling/query?q=Select DurableId from AccountSettings
```
## Supported Versions
39.0, 40.0

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
      "url" : "/services/data/v39.0/tooling/sobjects/AccountSettings/{DurableId}"
    },
    "DurableId" : "{DurableId}"
  } ]
}
```
