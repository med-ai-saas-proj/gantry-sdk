
# TokenTextSplitterOptions


## Properties

Name | Type
------------ | -------------
`encodingName` | string
`modelName` | string
`allowedSpecial` | [AllowedSpecial](AllowedSpecial.md)
`disallowedSpecial` | [DisallowedSpecial](DisallowedSpecial.md)
`chunkSize` | number
`chunkOverlap` | number

## Example

```typescript
import type { TokenTextSplitterOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "encodingName": null,
  "modelName": null,
  "allowedSpecial": null,
  "disallowedSpecial": null,
  "chunkSize": null,
  "chunkOverlap": null,
} satisfies TokenTextSplitterOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as TokenTextSplitterOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


