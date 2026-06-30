
# CharacterTextSplitterOptions


## Properties

Name | Type
------------ | -------------
`separator` | string
`isSeparatorRegex` | boolean
`chunkSize` | number
`chunkOverlap` | number
`keepSeparator` | [KeepSeparator](KeepSeparator.md)

## Example

```typescript
import type { CharacterTextSplitterOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "separator": null,
  "isSeparatorRegex": null,
  "chunkSize": null,
  "chunkOverlap": null,
  "keepSeparator": null,
} satisfies CharacterTextSplitterOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as CharacterTextSplitterOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


