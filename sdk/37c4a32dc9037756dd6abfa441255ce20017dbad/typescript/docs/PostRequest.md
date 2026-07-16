
# PostRequest


## Properties

Name | Type
------------ | -------------
`apiKeyUuid` | string
`amount` | [ScaledAmount](ScaledAmount.md)
`details` | { [key: string]: any; }
`capture` | boolean

## Example

```typescript
import type { PostRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "apiKeyUuid": null,
  "amount": null,
  "details": null,
  "capture": null,
} satisfies PostRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as PostRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


