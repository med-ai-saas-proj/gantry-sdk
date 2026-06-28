
# AddTextToRagRequest

DTO for adding text (with embedding) to a RAG bucket without an associated file. This can be used for ad-hoc knowledge that doesn\'t come from a file.

## Properties

Name | Type
------------ | -------------
`text` | [Text](Text.md)
`lang` | string
`chunkSplitter` | [ChunkSplitterType](ChunkSplitterType.md)
`chunkSplitterOptions` | [ChunkSplitterOptions](ChunkSplitterOptions.md)
`chunkSize` | number
`chunkOverlap` | number
`metadata` | { [key: string]: any; }

## Example

```typescript
import type { AddTextToRagRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "text": null,
  "lang": null,
  "chunkSplitter": null,
  "chunkSplitterOptions": null,
  "chunkSize": null,
  "chunkOverlap": null,
  "metadata": null,
} satisfies AddTextToRagRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as AddTextToRagRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


