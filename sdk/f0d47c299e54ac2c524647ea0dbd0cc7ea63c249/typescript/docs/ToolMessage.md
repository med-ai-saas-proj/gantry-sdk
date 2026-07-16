
# ToolMessage

A tool result message.

## Properties

Name | Type
------------ | -------------
`id` | string
`role` | string
`content` | string
`toolCallId` | string
`error` | string
`encryptedValue` | string

## Example

```typescript
import type { ToolMessage } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "role": null,
  "content": null,
  "toolCallId": null,
  "error": null,
  "encryptedValue": null,
} satisfies ToolMessage

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ToolMessage
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


