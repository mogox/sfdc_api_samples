# Sample Description
Simple request of an ApexCodeCoverageAggregate record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, ApexClassorTriggerId, NumLinesCovered, NumLinesUncovered, Coverage, CoverageLastModifiedDate from ApexCodeCoverageAggregate where ApexClassorTriggerId = '{ApexClassorTriggerId}'
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
  "entityTypeName": "ApexCodeCoverageAggregate",
  "queryLocator": null,
  "records": [
    {
      "ApexClassOrTriggerId": "{ApexClassOrTriggerId}",
      "Coverage": {
        "coveredLines": [
          3,
          8,
          9
        ],
        "uncoveredLines": []
      },
      "CoverageLastModifiedDate": null,
      "Id": "{ID}",
      "NumLinesCovered": 3,
      "NumLinesUncovered": 0,
      "attributes": {
        "type": "ApexCodeCoverageAggregate",
        "url": "/services/data/{version}/tooling/sobjects/ApexCodeCoverageAggregate/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
