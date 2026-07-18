
# QueryRagQueryByTextRequest

DTO for querying RAG embeddings by text.

## Properties

Name | Type
------------ | -------------
`queryText` | string
`topK` | number
`filters` | [Filters](Filters.md)
`hybridSearch` | boolean
`hybridSearchBm25TopK` | number
`hybridSearchSemanticTopK` | number
`hybridSearchBm25Lang` | string

## Example

```typescript
import type { QueryRagQueryByTextRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "queryText": null,
  "topK": null,
  "filters": null,
  "hybridSearch": null,
  "hybridSearchBm25TopK": null,
  "hybridSearchSemanticTopK": null,
  "hybridSearchBm25Lang": null,
} satisfies QueryRagQueryByTextRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as QueryRagQueryByTextRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


