# Sample Description
Simple request of an ActivitiesSettings record

## PATH
```
/services/data/{version}/tooling/query?q=Select DurableId from ActivitiesSettings
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

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
      "url" : "/services/data/{version}/tooling/sobjects/ActivitiesSettings/{DurableId}"
    },
    "DurableId" : "{DurableId}"
  } ]
}
```
