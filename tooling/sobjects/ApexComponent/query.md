# Sample Description
Query request of an ApexComponent record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, Description, Markup, MasterLabel, Name, NamespacePrefix from ApexComponent where Id = '{Id}'
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
  "done": true,
  "entityTypeName": "ApexComponent",
  "queryLocator": null,
  "records": [
    {
      "Description": "Apiato Test Component",
      "Id": "{ID}",
      "Markup": "<apex:component >\n  <h1>Apiato VF Component</h1>\n</apex:component>",
      "MasterLabel": "ApiatoComponent",
      "Name": "ApiatoComponent",
      "NamespacePrefix": null,
      "attributes": {
        "type": "ApexComponent",
        "url": "/services/data/v39.0/tooling/sobjects/ApexComponent/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
