
# AddRagFileRequest

DTO for adding a file (with embedding) to a RAG bucket.

## Properties

Name | Type
------------ | -------------
`fileUid` | string
`lang` | string
`chunkSplitter` | [ChunkSplitterType](ChunkSplitterType.md)
`chunkSplitterOptions` | [ChunkSplitterOptions](ChunkSplitterOptions.md)
`chunkSize` | number
`chunkOverlap` | number

## Example

```typescript
import type { AddRagFileRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "fileUid": null,
  "lang": null,
  "chunkSplitter": null,
  "chunkSplitterOptions": null,
  "chunkSize": null,
  "chunkOverlap": null,
} satisfies AddRagFileRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as AddRagFileRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


