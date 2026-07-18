
# ToolCallChunkEvent

Event containing a chunk of tool call content.

## Properties

Name | Type
------------ | -------------
`type` | string
`timestamp` | number
`rawEvent` | [](.md)
`toolCallId` | string
`toolCallName` | string
`parentMessageId` | string
`delta` | string

## Example

```typescript
import type { ToolCallChunkEvent } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "timestamp": null,
  "rawEvent": null,
  "toolCallId": null,
  "toolCallName": null,
  "parentMessageId": null,
  "delta": null,
} satisfies ToolCallChunkEvent

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ToolCallChunkEvent
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


