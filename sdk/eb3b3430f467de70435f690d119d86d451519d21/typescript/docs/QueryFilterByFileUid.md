
# QueryFilterByFileUid

DTO for querying RAG embeddings with file UID filters.

## Properties

Name | Type
------------ | -------------
`fileUids` | Array&lt;string&gt;

## Example

```typescript
import type { QueryFilterByFileUid } from ''

// TODO: Update the object below with actual values
const example = {
  "fileUids": null,
} satisfies QueryFilterByFileUid

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as QueryFilterByFileUid
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


