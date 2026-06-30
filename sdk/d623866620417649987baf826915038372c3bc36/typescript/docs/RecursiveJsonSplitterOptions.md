
# RecursiveJsonSplitterOptions


## Properties

Name | Type
------------ | -------------
`maxChunkSize` | number
`minChunkSize` | number
`convertLists` | boolean

## Example

```typescript
import type { RecursiveJsonSplitterOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "maxChunkSize": null,
  "minChunkSize": null,
  "convertLists": null,
} satisfies RecursiveJsonSplitterOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as RecursiveJsonSplitterOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


