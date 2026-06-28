
# SystemMessage

A system message.

## Properties

Name | Type
------------ | -------------
`id` | string
`role` | string
`content` | string
`name` | string
`encryptedValue` | string

## Example

```typescript
import type { SystemMessage } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "role": null,
  "content": null,
  "name": null,
  "encryptedValue": null,
} satisfies SystemMessage

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as SystemMessage
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


