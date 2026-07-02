
# MessagesInner


## Properties

Name | Type
------------ | -------------
`id` | string
`role` | string
`content` | string
`name` | string
`encryptedValue` | string
`toolCalls` | [Array&lt;ToolCall&gt;](ToolCall.md)
`toolCallId` | string
`error` | string
`activityType` | string

## Example

```typescript
import type { MessagesInner } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "role": null,
  "content": null,
  "name": null,
  "encryptedValue": null,
  "toolCalls": null,
  "toolCallId": null,
  "error": null,
  "activityType": null,
} satisfies MessagesInner

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as MessagesInner
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


