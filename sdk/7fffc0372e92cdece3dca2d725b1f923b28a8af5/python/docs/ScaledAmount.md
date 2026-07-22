# ScaledAmount

Fixed-point monetary amount — avoids float/Decimal in API inputs.  actual_value = value / 10^scale Example: 3.14159 USD → {\"value\": 314159, \"scale\": 5}  Reference: https://stackoverflow.com/a/77703260/31748896

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**value** | **int** |  | 
**scale** | **int** |  | 

## Example

```python
from openapi_client.models.scaled_amount import ScaledAmount

# TODO update the JSON string below
json = "{}"
# create an instance of ScaledAmount from a JSON string
scaled_amount_instance = ScaledAmount.from_json(json)
# print the JSON string representation of the object
print(ScaledAmount.to_json())

# convert the object into a dict
scaled_amount_dict = scaled_amount_instance.to_dict()
# create an instance of ScaledAmount from a dict
scaled_amount_from_dict = ScaledAmount.from_dict(scaled_amount_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


