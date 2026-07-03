
# HTMLSemanticPreservingSplitterOptions


## Properties

Name | Type
------------ | -------------
`headersToSplitOn` | Array&lt;Array&lt;any&gt;&gt;
`maxChunkSize` | number
`chunkOverlap` | number
`separators` | Array&lt;string&gt;
`elementsToPreserve` | Array&lt;string&gt;
`preserveLinks` | boolean
`preserveImages` | boolean
`preserveVideos` | boolean
`preserveAudio` | boolean
`customHandlers` | { [key: string]: any; }
`stopwordRemoval` | boolean
`stopwordLang` | string
`normalizeText` | boolean
`externalMetadata` | { [key: string]: string; }
`allowlistTags` | Array&lt;string&gt;
`denylistTags` | Array&lt;string&gt;
`preserveParentMetadata` | boolean
`keepSeparator` | [KeepSeparator](KeepSeparator.md)

## Example

```typescript
import type { HTMLSemanticPreservingSplitterOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "headersToSplitOn": null,
  "maxChunkSize": null,
  "chunkOverlap": null,
  "separators": null,
  "elementsToPreserve": null,
  "preserveLinks": null,
  "preserveImages": null,
  "preserveVideos": null,
  "preserveAudio": null,
  "customHandlers": null,
  "stopwordRemoval": null,
  "stopwordLang": null,
  "normalizeText": null,
  "externalMetadata": null,
  "allowlistTags": null,
  "denylistTags": null,
  "preserveParentMetadata": null,
  "keepSeparator": null,
} satisfies HTMLSemanticPreservingSplitterOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as HTMLSemanticPreservingSplitterOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


