
# ScaledAmount

Fixed-point monetary amount — avoids float/Decimal in API inputs.  actual_value = value / 10^scale Example: 3.14159 USD → {\"value\": 314159, \"scale\": 5}  Reference: https://stackoverflow.com/a/77703260/31748896

## Properties

Name | Type
------------ | -------------
`value` | number
`scale` | number

## Example

```typescript
import type { ScaledAmount } from ''

// TODO: Update the object below with actual values
const example = {
  "value": null,
  "scale": null,
} satisfies ScaledAmount

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ScaledAmount
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


