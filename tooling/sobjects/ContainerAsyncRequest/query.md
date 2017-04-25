# Sample Description
Query request of an ContainerAsyncRequest record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, MetadataContainerId, State, IsCheckOnly, IsDeleted, IsRunTests, ErrorMsg From ContainerAsyncRequest where Id = '{ID}'
```

## Supported Versions
39.0

## request
 ```json
{}
```

## response
```json
{
  "done": true,
  "entityTypeName": "ContainerAsyncRequest",
  "queryLocator": null,
  "records": [
    {
      "ErrorMsg": null,
      "Id": "{ID}",
      "IsCheckOnly": false,
      "IsDeleted": false,
      "IsRunTests": false,
      "MetadataContainerId": "{MetadataContainer ID}",
      "State": "Completed",
      "attributes": {
        "type": "ContainerAsyncRequest",
        "url": "/services/data/v39.0/tooling/sobjects/ContainerAsyncRequest/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
