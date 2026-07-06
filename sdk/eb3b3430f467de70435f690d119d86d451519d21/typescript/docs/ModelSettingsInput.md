
# ModelSettingsInput


## Properties

Name | Type
------------ | -------------
`maxTokens` | number
`temperature` | number
`topP` | number
`timeout` | number
`parallelToolCalls` | boolean
`seed` | number
`presencePenalty` | number
`frequencyPenalty` | number
`logitBias` | { [key: string]: number; }
`stopSequences` | Array&lt;string&gt;
`thinking` | [Thinking](Thinking.md)
`serviceTier` | string

## Example

```typescript
import type { ModelSettingsInput } from ''

// TODO: Update the object below with actual values
const example = {
  "maxTokens": null,
  "temperature": null,
  "topP": null,
  "timeout": null,
  "parallelToolCalls": null,
  "seed": null,
  "presencePenalty": null,
  "frequencyPenalty": null,
  "logitBias": null,
  "stopSequences": null,
  "thinking": null,
  "serviceTier": null,
} satisfies ModelSettingsInput

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ModelSettingsInput
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


