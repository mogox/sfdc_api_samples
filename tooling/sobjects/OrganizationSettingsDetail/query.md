# Sample Description
Simple request of an OrganizationSettingsDetail record

## PATH
```
/services/data/{version}/tooling/query/?q=select id, DurableId, SettingValue, SettingName from OrganizationSettingsDetail
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
 { }
```

## response
```json
{
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "OrganizationSettingsDetail",
  "records": [
    {
      "attributes": {
        "type": "OrganizationSettingsDetail",
        "url": "/services/data/{version}/tooling/sobjects/OrganizationSettingsDetail/{DurableId}"
      },
      "Id": "{ID}",
      "DurableId": "{DurableId}",
      "SettingValue": false,
      "SettingName": "NetworksEnabled"
    }
  ]
}
```
