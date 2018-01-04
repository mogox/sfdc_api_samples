# Sample Description
Simple request of an AppMenuItem record

## PATH
```
/services/data/v41.0/query/?q=select Id, SortOrder, Name, NamespacePrefix, Label, Description, StartUrl, MobileStartUrl, LogoUrl, IconUrl, InfoUrl, IsUsingAdminAuthorization, MobilePlatform, MobileMinOsVer, MobileDeviceType, IsRegisteredDeviceOnly, MobileAppVer, MobileAppInstalledDate, MobileAppInstalledVersion, MobileAppBinaryId, MobileAppInstallUrl, CanvasEnabled, CanvasReferenceId, CanvasUrl, CanvasAccessMethod, CanvasSelectedLocations, CanvasOptions, Type, ApplicationId, UserSortOrder, IsVisible, IsAccessible from AppMenuItem
```
## Supported Versions
41.0

## request
 ```json
 { }
```

## response
```json
{
  "totalSize": 1,
  "done": true,
  "records": [
    {
      "attributes": {
        "type": "AppMenuItem",
        "url": "/services/data/v41.0/sobjects/AppMenuItem/{ID}"
      },
      "Id": "{ID}",
      "SortOrder": 11,
      "Name": "Sites",
      "NamespacePrefix": "standard",
      "Label": "Site.com",
      "Description": "Build pixel-perfect, data-rich websites using the drag-and-drop Site.com application, and manage content and published sites.",
      "StartUrl": "https://na35.salesforce.com/home/home.jsp?tsid={ApplicationID}",
      "MobileStartUrl": null,
      "LogoUrl": "https://na35.salesforce.com/logos/app/{OrgID}/{ApplicationID}",
      "IconUrl": "https://na35.salesforce.com/logos/Salesforce/Sites/icon.png",
      "InfoUrl": null,
      "IsUsingAdminAuthorization": true,
      "MobilePlatform": null,
      "MobileMinOsVer": null,
      "MobileDeviceType": null,
      "IsRegisteredDeviceOnly": false,
      "MobileAppVer": null,
      "MobileAppInstalledDate": null,
      "MobileAppInstalledVersion": null,
      "MobileAppBinaryId": null,
      "MobileAppInstallUrl": null,
      "CanvasEnabled": false,
      "CanvasReferenceId": null,
      "CanvasUrl": null,
      "CanvasAccessMethod": null,
      "CanvasSelectedLocations": null,
      "CanvasOptions": null,
      "Type": "TabSet",
      "ApplicationId": "{ApplicationID}",
      "UserSortOrder": null,
      "IsVisible": true,
      "IsAccessible": true
    }
  ]
}
```
