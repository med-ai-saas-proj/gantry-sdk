
# RunAgentInputWithModelSettings


## Properties

Name | Type
------------ | -------------
`threadId` | string
`runId` | string
`parentRunId` | string
`state` | any
`messages` | [Array&lt;MessagesInner&gt;](MessagesInner.md)
`tools` | [Array&lt;Tool&gt;](Tool.md)
`context` | [Array&lt;Context&gt;](Context.md)
`forwardedProps` | any
`modelSettings` | [ModelSettingsInput](ModelSettingsInput.md)
`systemPrompt` | [Systemprompt](Systemprompt.md)
`maxTurns` | number
`reservedTokens` | number

## Example

```typescript
import type { RunAgentInputWithModelSettings } from ''

// TODO: Update the object below with actual values
const example = {
  "threadId": null,
  "runId": null,
  "parentRunId": null,
  "state": null,
  "messages": null,
  "tools": null,
  "context": null,
  "forwardedProps": null,
  "modelSettings": null,
  "systemPrompt": null,
  "maxTurns": null,
  "reservedTokens": null,
} satisfies RunAgentInputWithModelSettings

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as RunAgentInputWithModelSettings
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


