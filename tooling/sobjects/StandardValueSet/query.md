# Sample Description
Simple request of an StandardValueSet record

## PATH
```
/services/data/v40.0/tooling/query/?q=Select Fullname, MasterLabel, DurableId, Metadata from StandardValueSet where DurableId = '{StandardValueSet Name}'
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
  "entityTypeName": "StandardValueSet",
  "queryLocator": null,
  "records": [
    {
      "DurableId": "{StandardValueSet Name}",
      "FullName": "{StandardValueSet Name}",
      "MasterLabel": "{StandardValueSet Name}",
      "Metadata": {
        "groupingStringEnum": null,
        "sorted": false,
        "standardValue": [
          {
            "allowEmail": null,
            "closed": false,
            "color": null,
            "converted": null,
            "cssExposed": null,
            "default": true,
            "description": null,
            "forecastCategory": null,
            "groupingString": null,
            "highPriority": null,
            "isActive": null,
            "label": "New",
            "probability": null,
            "reverseRole": null,
            "reviewed": null,
            "urls": null,
            "valueName": "New",
            "won": null
          },
          {
            "allowEmail": null,
            "closed": false,
            "color": null,
            "converted": null,
            "cssExposed": null,
            "default": false,
            "description": null,
            "forecastCategory": null,
            "groupingString": null,
            "highPriority": null,
            "isActive": null,
            "label": "Working",
            "probability": null,
            "reverseRole": null,
            "reviewed": null,
            "urls": null,
            "valueName": "Working",
            "won": null
          },
          {
            "allowEmail": null,
            "closed": false,
            "color": null,
            "converted": null,
            "cssExposed": null,
            "default": false,
            "description": null,
            "forecastCategory": null,
            "groupingString": null,
            "highPriority": null,
            "isActive": null,
            "label": "Escalated",
            "probability": null,
            "reverseRole": null,
            "reviewed": null,
            "urls": null,
            "valueName": "Escalated",
            "won": null
          },
          {
            "allowEmail": null,
            "closed": true,
            "color": null,
            "converted": null,
            "cssExposed": null,
            "default": false,
            "description": null,
            "forecastCategory": null,
            "groupingString": null,
            "highPriority": null,
            "isActive": null,
            "label": "Closed",
            "probability": null,
            "reverseRole": null,
            "reviewed": null,
            "urls": null,
            "valueName": "Closed",
            "won": null
          }
        ],
        "urls": null
      },
      "attributes": {
        "type": "StandardValueSet",
        "url": "/services/data/v40.0/tooling/sobjects/StandardValueSet/{StandardValueSet Name}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```