
# ReasoningEncryptedValueEvent

Event containing an encrypted value for a message or tool call.

## Properties

Name | Type
------------ | -------------
`type` | string
`timestamp` | number
`rawEvent` | [](.md)
`subtype` | string
`entityId` | string
`encryptedValue` | string

## Example

```typescript
import type { ReasoningEncryptedValueEvent } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "timestamp": null,
  "rawEvent": null,
  "subtype": null,
  "entityId": null,
  "encryptedValue": null,
} satisfies ReasoningEncryptedValueEvent

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ReasoningEncryptedValueEvent
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


