# Sample Description
GET request for CustomFieldMember record

## PATH
```
/services/data/v39.0/tooling/sobjects/CustomFieldMember/{ID}
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
  "Content": "<?xml version=\"1.0\" encoding=\"UTF-8\"?>\n<CustomField xmlns=\"urn:metadata.tooling.soap.sforce.com\">\n    <externalId>false</externalId>\n    <label>Apiato Text Field</label>\n    <length>100</length>\n    <required>false</required>\n    <trackTrending>false</trackTrending>\n    <type>Text</type>\n    <unique>false</unique>\n</CustomField>",
  "ContentEntityId": null,
  "CreatedById": "{UserId}",
  "CreatedDate": "2017-04-25T17:25:13.000+0000",
  "FullName": "Account.apiato_txt__c",
  "Id": "{ID}",
  "IsDeleted": false,
  "LastModifiedById": "{UserId}",
  "LastModifiedDate": "2017-04-25T17:25:13.000+0000",
  "LastSyncDate": null,
  "Metadata": {
    "caseSensitive": null,
    "customDataType": null,
    "defaultValue": null,
    "deleteConstraint": null,
    "deprecated": null,
    "description": null,
    "displayFormat": null,
    "displayLocationInDecimal": null,
    "encrypted": null,
    "escapeMarkup": null,
    "externalDeveloperName": null,
    "externalId": false,
    "formula": null,
    "formulaTreatBlanksAs": null,
    "inlineHelpText": null,
    "isConvertLeadDisabled": null,
    "isFilteringDisabled": null,
    "isNameField": null,
    "isSortingDisabled": null,
    "label": "Apiato Text Field",
    "length": 100,
    "lookupFilter": null,
    "maskChar": null,
    "maskType": null,
    "metadataRelationshipControllingField": null,
    "populateExistingRows": null,
    "precision": null,
    "readOnlyProxy": null,
    "referenceTargetField": null,
    "referenceTo": null,
    "relationshipLabel": null,
    "relationshipName": null,
    "relationshipOrder": null,
    "reparentableMasterDetail": null,
    "required": false,
    "restrictedAdminField": null,
    "scale": null,
    "startingNumber": null,
    "stripMarkup": null,
    "summarizedField": null,
    "summaryFilterItems": null,
    "summaryForeignKey": null,
    "summaryOperation": null,
    "trackFeedHistory": null,
    "trackHistory": null,
    "trackTrending": false,
    "type": "Text",
    "unique": false,
    "urls": null,
    "valueSet": null,
    "visibleLines": null,
    "writeRequiresMasterRead": null
  },
  "MetadataContainerId": "{ID}",
  "SystemModstamp": "2017-04-25T17:25:13.000+0000",
  "attributes": {
    "type": "CustomFieldMember",
    "url": "/services/data/v39.0/tooling/sobjects/CustomFieldMember/{ID}"
  }
}
```
