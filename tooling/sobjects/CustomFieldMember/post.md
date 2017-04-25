# Sample Description
POST request for CustomFieldMember record

## PATH
```
/services/data/v39.0/tooling/sobjects/CustomFieldMember/
```
## Supported Versions
39.0

## request
 ```json
 {
     "MetadataContainerId": "<MetadataContainer Id>",
     "FullName" : "Account.apiato_txt",
     "Metadata" : {
       "caseSensitive" : null,
       "customDataType" : null,
       "defaultValue" : null,
       "deleteConstraint" : null,
       "deprecated" : null,
       "description" : null,
       "displayFormat" : null,
       "displayLocationInDecimal" : null,
       "encrypted" : null,
       "escapeMarkup" : null,
       "externalDeveloperName" : null,
       "externalId" : false,
       "formula" : null,
       "formulaTreatBlanksAs" : null,
       "inlineHelpText" : null,
       "isConvertLeadDisabled" : null,
       "isFilteringDisabled" : null,
       "isNameField" : null,
       "isSortingDisabled" : null,
       "label" : "Apiato Text Field",
       "length" : 100,
       "lookupFilter" : null,
       "maskChar" : null,
       "maskType" : null,
       "picklist" : null,
       "populateExistingRows" : null,
       "precision" : null,
       "readOnlyProxy" : null,
       "referenceTargetField" : null,
       "referenceTo" : null,
       "relationshipLabel" : null,
       "relationshipName" : null,
       "relationshipOrder" : null,
       "reparentableMasterDetail" : null,
       "required" : false,
       "restrictedAdminField" : null,
       "scale" : null,
       "startingNumber" : null,
       "stripMarkup" : null,
       "summarizedField" : null,
       "summaryForeignKey" : null,
       "summaryOperation" : null,
       "trackFeedHistory" : null,
       "trackHistory" : null,
       "trackTrending" : false,
       "type" : "Text",
       "unique" : false,
       "urls" : null,
       "valueSet" : null,
       "visibleLines" : null,
       "writeRequiresMasterRead" : null
     }
 }
```

## request description
This sample creates a 100 character text field on the Account object. It can be used to create a custom field on both standard and custom objects depending on what you set on FullName (format = <standard or custom Object API name>.<Custom Field API Name>).

## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
