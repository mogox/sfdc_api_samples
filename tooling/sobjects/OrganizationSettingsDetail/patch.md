# Sample Description
PATCH request of an OrganizationSettingsDetail record

## PATH
```
/services/data/{version}/tooling/sobjects/OrganizationSettingsDetail/{DurableId}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
    "SettingValue": true,
    "SettingName": "NetworksEnabled"
}
```

## request description
This sample updates NetworksEnabled setting from false to true.

## response
```json
{}
```
