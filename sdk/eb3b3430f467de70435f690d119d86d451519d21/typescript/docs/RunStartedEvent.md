
# RunStartedEvent

Event indicating that a run has started.

## Properties

Name | Type
------------ | -------------
`type` | string
`timestamp` | number
`rawEvent` | [](.md)
`threadId` | string
`runId` | string
`parentRunId` | string
`input` | [RunAgentInput](RunAgentInput.md)

## Example

```typescript
import type { RunStartedEvent } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "timestamp": null,
  "rawEvent": null,
  "threadId": null,
  "runId": null,
  "parentRunId": null,
  "input": null,
} satisfies RunStartedEvent

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as RunStartedEvent
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


