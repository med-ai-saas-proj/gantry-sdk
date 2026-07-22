
# ReasoningMessageEndEvent

Event indicating the end of a reasoning message.

## Properties

Name | Type
------------ | -------------
`type` | string
`timestamp` | number
`rawEvent` | [](.md)
`messageId` | string

## Example

```typescript
import type { ReasoningMessageEndEvent } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "timestamp": null,
  "rawEvent": null,
  "messageId": null,
} satisfies ReasoningMessageEndEvent

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ReasoningMessageEndEvent
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


