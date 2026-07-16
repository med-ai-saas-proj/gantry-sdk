
# ContentAnyOfInner


## Properties

Name | Type
------------ | -------------
`type` | string
`text` | string
`source` | [Source](Source.md)
`metadata` | [](.md)
`mimeType` | string
`id` | string
`url` | string
`data` | string
`filename` | string

## Example

```typescript
import type { ContentAnyOfInner } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "text": null,
  "source": null,
  "metadata": null,
  "mimeType": null,
  "id": null,
  "url": null,
  "data": null,
  "filename": null,
} satisfies ContentAnyOfInner

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ContentAnyOfInner
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


