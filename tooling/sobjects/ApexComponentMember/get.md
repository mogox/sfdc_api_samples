# Sample Description
Simple request of an ApexComponentMember record

## PATH
```
/services/data/v39.0/tooling/sobjects/ApexComponentMember/{ID}
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
  "Body": "<apex:component >\n  <h1>Apiato VF Component</h1>\n</apex:component>",
  "Content": "<?xml version=\"1.0\" encoding=\"UTF-8\"?>\n<ApexComponent xmlns=\"urn:metadata.tooling.soap.sforce.com\">\n    <apiVersion>39.0</apiVersion>\n    <description>Apiato Description Patch</description>\n    <label>ApiatoComponent</label>\n</ApexComponent>",
  "ContentEntityId": "{ComponentID}",
  "CreatedById": "00541000000uEgSAAU",
  "CreatedDate": "2017-03-28T01:27:23.000+0000",
  "FullName": "UniqueName_ACmpM",
  "Id": "{ID}",
  "IsDeleted": false,
  "LastModifiedById": "00541000000uEgSAAU",
  "LastModifiedDate": "2017-03-28T01:27:23.000+0000",
  "LastSyncDate": "2017-03-28T01:09:02.000+0000",
  "Metadata": {
    "apiVersion": 39,
    "description": "Apiato Test Component",
    "label": "ApiatoComponent",
    "packageVersions": null,
    "urls": null
  },
  "MetadataContainerId": "{MetadataContainerID}",
  "SystemModstamp": "2017-03-28T01:27:23.000+0000",
  "attributes": {
    "type": "ApexComponentMember",
    "url": "/services/data/v39.0/tooling/sobjects/ApexComponentMember/{ID}"
  }
}
```
