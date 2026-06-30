
# Filters


## Properties

Name | Type
------------ | -------------
`fileMetadataFilters` | [{ [key: string]: FileMetadataFiltersValue; }](FileMetadataFiltersValue.md)
`fileUids` | Array&lt;string&gt;

## Example

```typescript
import type { Filters } from ''

// TODO: Update the object below with actual values
const example = {
  "fileMetadataFilters": null,
  "fileUids": null,
} satisfies Filters

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as Filters
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


