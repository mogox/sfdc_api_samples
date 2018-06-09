# Sample Description
Query request of an ApexComponent record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, Description, Markup, MasterLabel, Name, NamespacePrefix from ApexComponent where Id = '{Id}'
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
        "url": "/services/data/{version}/tooling/sobjects/ApexComponent/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
