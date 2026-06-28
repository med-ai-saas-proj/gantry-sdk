
# ResponseAgUiGatewayAiGatewayAgUiModelPost


## Properties

Name | Type
------------ | -------------
`type` | string
`timestamp` | number
`rawEvent` | [](.md)
`messageId` | string
`role` | string
`name` | string
`delta` | string
`toolCallId` | string
`toolCallName` | string
`parentMessageId` | string
`content` | any
`title` | string
`snapshot` | any
`messages` | [Array&lt;MessagesInner&gt;](MessagesInner.md)
`activityType` | string
`replace` | boolean
`patch` | Array&lt;any&gt;
`event` | any
`source` | string
`value` | any
`threadId` | string
`runId` | string
`parentRunId` | string
`input` | [RunAgentInput](RunAgentInput.md)
`result` | [](.md)
`message` | string
`code` | string
`stepName` | string
`subtype` | string
`entityId` | string
`encryptedValue` | string

## Example

```typescript
import type { ResponseAgUiGatewayAiGatewayAgUiModelPost } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "timestamp": null,
  "rawEvent": null,
  "messageId": null,
  "role": null,
  "name": null,
  "delta": null,
  "toolCallId": null,
  "toolCallName": null,
  "parentMessageId": null,
  "content": null,
  "title": null,
  "snapshot": null,
  "messages": null,
  "activityType": null,
  "replace": null,
  "patch": null,
  "event": null,
  "source": null,
  "value": null,
  "threadId": null,
  "runId": null,
  "parentRunId": null,
  "input": null,
  "result": null,
  "message": null,
  "code": null,
  "stepName": null,
  "subtype": null,
  "entityId": null,
  "encryptedValue": null,
} satisfies ResponseAgUiGatewayAiGatewayAgUiModelPost

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ResponseAgUiGatewayAiGatewayAgUiModelPost
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


