
# ReasoningStartEvent

Event indicating the start of a reasoning phase.

## Properties

Name | Type
------------ | -------------
`type` | string
`timestamp` | number
`rawEvent` | [](.md)
`messageId` | string

## Example

```typescript
import type { ReasoningStartEvent } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "timestamp": null,
  "rawEvent": null,
  "messageId": null,
} satisfies ReasoningStartEvent

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ReasoningStartEvent
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


