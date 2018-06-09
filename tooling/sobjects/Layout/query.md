# Sample Description
Simple request of an Layout record

## PATH
```
/services/data/{version}/tooling/query/?q=select Id, EntityDefinitionId, Fullname, LayoutType, ManageableState, Metadata, Name, NamespacePrefix, ShowSubmitAndAttachButton, TableEnumOrId from Layout where Name = '{Layout Name}'
```
## Supported Versions
39.0, 40.0

## request
 ```json
 { }
```

## response
```json
{
  "done": true,
  "entityTypeName": "Layout",
  "queryLocator": null,
  "records": [
    {
      "EntityDefinitionId": "{Object Id}",
      "FullName": "{Object API Name-Layout Name}",
      "Id": "{ID}",
      "LayoutType": "Standard",
      "ManageableState": "unmanaged",
      "Metadata": {
        "customButtons": [],
        "customConsoleComponents": null,
        "emailDefault": null,
        "excludeButtons": [
          "Submit"
        ],
        "feedLayout": null,
        "headers": null,
        "layoutSections": [
          {
            "customLabel": false,
            "detailHeading": false,
            "editHeading": true,
            "label": "Information",
            "layoutColumns": [
              {
                "layoutItems": [
                  {
                    "analyticsCloudComponent": null,
                    "behavior": "Required",
                    "canvas": null,
                    "component": null,
                    "customLink": null,
                    "emptySpace": null,
                    "field": "Name",
                    "height": null,
                    "page": null,
                    "reportChartComponent": null,
                    "scontrol": null,
                    "showLabel": null,
                    "showScrollbars": null,
                    "width": null
                  },
                  {
                    "analyticsCloudComponent": null,
                    "behavior": "Edit",
                    "canvas": null,
                    "component": null,
                    "customLink": null,
                    "emptySpace": null,
                    "field": "fieldname__c",
                    "height": null,
                    "page": null,
                    "reportChartComponent": null,
                    "scontrol": null,
                    "showLabel": null,
                    "showScrollbars": null,
                    "width": null
                  },
                  {
                    "analyticsCloudComponent": null,
                    "behavior": "Edit",
                    "canvas": null,
                    "component": null,
                    "customLink": null,
                    "emptySpace": null,
                    "field": "objid__c",
                    "height": null,
                    "page": null,
                    "reportChartComponent": null,
                    "scontrol": null,
                    "showLabel": null,
                    "showScrollbars": null,
                    "width": null
                  }
                ],
                "reserved": null
              },
              {
                "layoutItems": [
                  {
                    "analyticsCloudComponent": null,
                    "behavior": "Edit",
                    "canvas": null,
                    "component": null,
                    "customLink": null,
                    "emptySpace": null,
                    "field": "OwnerId",
                    "height": null,
                    "page": null,
                    "reportChartComponent": null,
                    "scontrol": null,
                    "showLabel": null,
                    "showScrollbars": null,
                    "width": null
                  }
                ],
                "reserved": null
              }
            ],
            "style": "TwoColumnsTopToBottom"
          },
          {
            "customLabel": false,
            "detailHeading": false,
            "editHeading": true,
            "label": "System Information",
            "layoutColumns": [
              {
                "layoutItems": [
                  {
                    "analyticsCloudComponent": null,
                    "behavior": "Readonly",
                    "canvas": null,
                    "component": null,
                    "customLink": null,
                    "emptySpace": null,
                    "field": "CreatedById",
                    "height": null,
                    "page": null,
                    "reportChartComponent": null,
                    "scontrol": null,
                    "showLabel": null,
                    "showScrollbars": null,
                    "width": null
                  }
                ],
                "reserved": null
              },
              {
                "layoutItems": [
                  {
                    "analyticsCloudComponent": null,
                    "behavior": "Readonly",
                    "canvas": null,
                    "component": null,
                    "customLink": null,
                    "emptySpace": null,
                    "field": "LastModifiedById",
                    "height": null,
                    "page": null,
                    "reportChartComponent": null,
                    "scontrol": null,
                    "showLabel": null,
                    "showScrollbars": null,
                    "width": null
                  }
                ],
                "reserved": null
              }
            ],
            "style": "TwoColumnsTopToBottom"
          },
          {
            "customLabel": true,
            "detailHeading": false,
            "editHeading": true,
            "label": "カスタムリンク",
            "layoutColumns": [
              {
                "layoutItems": [],
                "reserved": null
              },
              {
                "layoutItems": [],
                "reserved": null
              },
              {
                "layoutItems": [],
                "reserved": null
              }
            ],
            "style": "CustomLinks"
          }
        ],
        "miniLayout": null,
        "multilineLayoutFields": null,
        "platformActionList": null,
        "quickActionList": null,
        "relatedContent": null,
        "relatedLists": null,
        "relatedObjects": [],
        "runAssignmentRulesDefault": null,
        "showEmailCheckbox": false,
        "showHighlightsPanel": false,
        "showInteractionLogPanel": false,
        "showKnowledgeComponent": null,
        "showRunAssignmentRulesCheckbox": false,
        "showSolutionSection": null,
        "showSubmitAndAttachButton": false,
        "summaryLayout": null,
        "urls": null
      },
      "Name": "{Layout Name}",
      "NamespacePrefix": null,
      "ShowSubmitAndAttachButton": false,
      "TableEnumOrId": "{Object Id}",
      "attributes": {
        "type": "Layout",
        "url": "/services/data/{version}/tooling/sobjects/Layout/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
