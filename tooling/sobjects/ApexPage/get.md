# Sample Description
GET request of a ApexPage record

## PATH
```
/services/data/v39.0/tooling/sobjects/ApexPage/{ID}
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
  "ApiVersion": 39,
  "ControllerKey": null,
  "ControllerType": "0",
  "CreatedById": "{User ID}",
  "CreatedDate": "2017-04-26T17:54:52.000+0000",
  "Description": "Apex Page sample from Apiato.",
  "FullName": "helloApiato",
  "Id": "{ID}",
  "IsAvailableInTouch": false,
  "IsConfirmationTokenRequired": false,
  "LastModifiedById": "{User ID}",
  "LastModifiedDate": "2017-04-26T17:54:52.000+0000",
  "ManageableState": "unmanaged",
  "Markup": "<apex:page >\n  <h1>Hello Apiato</h1>\n</apex:page>",
  "MasterLabel": "helloApiato",
  "Metadata": {
    "apiVersion": 39,
    "availableInTouch": false,
    "confirmationTokenRequired": false,
    "description": "Apex Page sample from Apiato.",
    "label": "helloApiato",
    "packageVersions": [],
    "urls": null
  },
  "Name": "helloApiato",
  "NamespacePrefix": null,
  "SystemModstamp": "2017-04-26T17:54:52.000+0000",
  "attributes": {
    "type": "ApexPage",
    "url": "/services/data/v39.0/tooling/sobjects/ApexPage/{ID}"
  }
}
```
