
# ActivityMessage

An activity progress message emitted between chat messages.

## Properties

Name | Type
------------ | -------------
`id` | string
`role` | string
`activityType` | string
`content` | { [key: string]: any; }

## Example

```typescript
import type { ActivityMessage } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "role": null,
  "activityType": null,
  "content": null,
} satisfies ActivityMessage

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ActivityMessage
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


