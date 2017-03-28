# Sample Description
Simple request of an ApexOrgWideCoverage record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, PercentCovered from ApexOrgWideCoverage where Id = '{ID}'
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
  "entityTypeName": "ApexOrgWideCoverage",
  "queryLocator": null,
  "records": [
    {
      "Id": "{ID}",
      "PercentCovered": 83,
      "attributes": {
        "type": "ApexOrgWideCoverage",
        "url": "/services/data/v39.0/tooling/sobjects/ApexOrgWideCoverage/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
