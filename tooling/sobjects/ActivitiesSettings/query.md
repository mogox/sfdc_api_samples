# Sample Description
Simple request of an ActivitiesSettings record

## PATH
```
/services/data/v39.0/tooling/query?q=Select DurableId from ActivitiesSettings
```
## Supported Versions
39.0

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
  "entityTypeName" : "ActivitiesSettings",
  "records" : [ {
    "attributes" : {
      "type" : "ActivitiesSettings",
      "url" : "/services/data/v39.0/tooling/sobjects/ActivitiesSettings/{DurableId}"
    },
    "DurableId" : "{DurableId}"
  } ]
}
```
