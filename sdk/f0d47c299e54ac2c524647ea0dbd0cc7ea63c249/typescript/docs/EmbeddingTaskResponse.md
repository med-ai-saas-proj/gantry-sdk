
# EmbeddingTaskResponse

DTO for RAG embedding task status response.

## Properties

Name | Type
------------ | -------------
`taskId` | string
`fileUid` | string
`text` | [Text1](Text1.md)
`metadata` | { [key: string]: any; }
`type` | string
`projectUuid` | string
`chunkSplitter` | [ChunkSplitterType](ChunkSplitterType.md)
`chunkSplitterOptions` | [ChunkSplitterOptions](ChunkSplitterOptions.md)
`chunkSize` | number
`chunkOverlap` | number
`failedReason` | string
`status` | string

## Example

```typescript
import type { EmbeddingTaskResponse } from ''

// TODO: Update the object below with actual values
const example = {
  "taskId": null,
  "fileUid": null,
  "text": null,
  "metadata": null,
  "type": null,
  "projectUuid": null,
  "chunkSplitter": null,
  "chunkSplitterOptions": null,
  "chunkSize": null,
  "chunkOverlap": null,
  "failedReason": null,
  "status": null,
} satisfies EmbeddingTaskResponse

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as EmbeddingTaskResponse
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


