
# RagQueryResponse

DTO for RAG query response.

## Properties

Name | Type
------------ | -------------
`fileInfo` | [FileInfoResponse](FileInfoResponse.md)
`text` | string
`embedding` | Array&lt;number&gt;
`createdAt` | Date
`metadata` | { [key: string]: any; }
`vectorDistance` | number
`bm25Score` | number
`rerankScore` | number

## Example

```typescript
import type { RagQueryResponse } from ''

// TODO: Update the object below with actual values
const example = {
  "fileInfo": null,
  "text": null,
  "embedding": null,
  "createdAt": null,
  "metadata": null,
  "vectorDistance": null,
  "bm25Score": null,
  "rerankScore": null,
} satisfies RagQueryResponse

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as RagQueryResponse
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


