# Sample Description
Query request of an CustomFieldMember record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, FullName, Metadata, MetadataContainerId, IsDeleted  From CustomFieldMember where Id = '{ID}'
```

## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
{}
```

## response
```json
{
  "done": true,
  "entityTypeName": "CustomFieldMember",
  "queryLocator": null,
  "records": [
    {
      "FullName": "Account.apiato_txt__c",
      "Id": "{ID}",
      "IsDeleted": false,
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
      "MetadataContainerId": "{MetadataContainer ID}",
      "attributes": {
        "type": "CustomFieldMember",
        "url": "/services/data/{version}/tooling/sobjects/CustomFieldMember/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
