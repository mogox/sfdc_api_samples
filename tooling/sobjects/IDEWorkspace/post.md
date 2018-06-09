# Sample Description
POST Request for IDEWorkspace

## PATH
```
/services/data/{version}/tooling/sobjects/IDEWorkspace
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{
  "Name": "DefaultWorkspace",
  "UserId": "{UserID}",
  "Content": "{}"
}
```

## request description
Create a new IDEWorkspace record called DefaultWorkspace. NOTE: This is used internally by the Developer Console.

## response
```json
{
  "id": "{ID}",
  "success": true,
  "errors": [],
  "warnings": []
}
```
