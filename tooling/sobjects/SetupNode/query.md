# Sample Description
QUERY request of a SetupNode record

## PATH
```
/services/data/v39.0/tooling/query/?q=select ExternalId, FullName, IconUrl, IsNew, NodeType, RelatedEntities, Tags, Url from SetupNode
```
## Supported Versions
39.0

## request
```json
{}
```
## request description
SetupNode is a read-only object that exposes information about Setup Menu Nodes.

## response
```json
{
  "done": true,
  "entityTypeName": "SetupNode",
  "queryLocator": null,
  "records": [
    {
      "ExternalId": null,
      "FullName": "SetupOneHome",
      "IconUrl": "/img/icon/setup/home-rest.png",
      "IsNew": false,
      "NodeType": "Setup",
      "RelatedEntities": null,
      "Tags": null,
      "Url": "CMP?retURL=%2Fsetup%2Fhome",
      "attributes": {
        "type": "SetupNode"
      }
    },
    {
      "ExternalId": null,
      "FullName": "SetupOneHome",
      "IconUrl": null,
      "IsNew": false,
      "NodeType": "ServiceSetup",
      "RelatedEntities": null,
      "Tags": null,
      "Url": "CMP?retURL=%2Fsetup%2Fhome%3FsetupApp%3Dservice",
      "attributes": {
        "type": "SetupNode"
      }
    }
  ],
  "size": 2,
  "totalSize": 2
}
```
