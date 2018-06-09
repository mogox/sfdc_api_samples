# Sample Description
QUERY request of a ApexPageInfo record

## PATH
```
/services/data/{version}/tooling/query/?q=select Id, ApexPageId, Name, NameSpacePrefix, ApiVersion, Description, IsAvailableInTouch, MasterLabel, DurableId from ApexPageInfo where ApexPageId = {ApexPage ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{}
```
## request description
ApexPageInfo is a read-only object that exposes information about ApexPage.

## response
```json
{
  "done": true,
  "entityTypeName": "ApexPageInfo",
  "queryLocator": null,
  "records": [
    {
      "ApexPageId": "{ApexPage ID}",
      "ApiVersion": 39,
      "Description": "Apex Page sample from Apiato.",
      "DurableId": "{DurableID}",
      "Id": "{ID}",
      "IsAvailableInTouch": true,
      "MasterLabel": "helloApiato",
      "Name": "helloApiato",
      "NameSpacePrefix": null,
      "attributes": {
        "type": "ApexPageInfo",
        "url": "/services/data/{version}/tooling/sobjects/ApexPageInfo/{DurableID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
