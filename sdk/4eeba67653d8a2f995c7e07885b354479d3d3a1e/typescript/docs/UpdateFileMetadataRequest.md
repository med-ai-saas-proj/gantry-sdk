
# UpdateFileMetadataRequest

DTO for updating file metadata.

## Properties

Name | Type
------------ | -------------
`extraMetadata` | [{ [key: string]: UpdateFileMetadataRequestExtraMetadataValue; }](UpdateFileMetadataRequestExtraMetadataValue.md)

## Example

```typescript
import type { UpdateFileMetadataRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "extraMetadata": null,
} satisfies UpdateFileMetadataRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as UpdateFileMetadataRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


