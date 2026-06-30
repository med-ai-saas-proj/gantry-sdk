
# ChunkSplitterOptions


## Properties

Name | Type
------------ | -------------
`separator` | string
`isSeparatorRegex` | boolean
`chunkSize` | number
`chunkOverlap` | number
`keepSeparator` | [KeepSeparator](KeepSeparator.md)
`separators` | Array&lt;string&gt;
`encodingName` | string
`modelName` | string
`allowedSpecial` | [AllowedSpecial](AllowedSpecial.md)
`disallowedSpecial` | [DisallowedSpecial](DisallowedSpecial.md)
`headersToSplitOn` | Array&lt;Array&lt;any&gt;&gt;
`returnEachLine` | boolean
`stripHeaders` | boolean
`customHeaderPatterns` | { [key: string]: number; }
`returnEachElement` | boolean
`maxChunkSize` | number
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
`minChunkSize` | number
`convertLists` | boolean
`language` | string
`useSpanTokenize` | boolean
`pipeline` | string
`maxLength` | number
`stripWhitespace` | boolean
`tokensPerChunk` | number
`modelKwargs` | { [key: string]: any; }

## Example

```typescript
import type { ChunkSplitterOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "separator": null,
  "isSeparatorRegex": null,
  "chunkSize": null,
  "chunkOverlap": null,
  "keepSeparator": null,
  "separators": null,
  "encodingName": null,
  "modelName": null,
  "allowedSpecial": null,
  "disallowedSpecial": null,
  "headersToSplitOn": null,
  "returnEachLine": null,
  "stripHeaders": null,
  "customHeaderPatterns": null,
  "returnEachElement": null,
  "maxChunkSize": null,
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
  "minChunkSize": null,
  "convertLists": null,
  "language": null,
  "useSpanTokenize": null,
  "pipeline": null,
  "maxLength": null,
  "stripWhitespace": null,
  "tokensPerChunk": null,
  "modelKwargs": null,
} satisfies ChunkSplitterOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ChunkSplitterOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


