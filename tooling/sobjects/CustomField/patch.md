# Sample Description
PATCH request of an CustomField record

## PATH
```
/services/data/{version}/tooling/sobjects/CustomField/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
{
    "FullName" : "{Object API Name}.{Field API Name}",
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
      "label" : "{My Custom Label}",
      "length" : 120,
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

## response
```json
{}
```
