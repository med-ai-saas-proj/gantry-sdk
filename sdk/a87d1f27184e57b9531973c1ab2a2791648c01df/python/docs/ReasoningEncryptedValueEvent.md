# ReasoningEncryptedValueEvent

Event containing an encrypted value for a message or tool call.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'REASONING_ENCRYPTED_VALUE']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**subtype** | **str** |  | 
**entity_id** | **str** |  | 
**encrypted_value** | **str** |  | 

## Example

```python
from openapi_client.models.reasoning_encrypted_value_event import ReasoningEncryptedValueEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ReasoningEncryptedValueEvent from a JSON string
reasoning_encrypted_value_event_instance = ReasoningEncryptedValueEvent.from_json(json)
# print the JSON string representation of the object
print(ReasoningEncryptedValueEvent.to_json())

# convert the object into a dict
reasoning_encrypted_value_event_dict = reasoning_encrypted_value_event_instance.to_dict()
# create an instance of ReasoningEncryptedValueEvent from a dict
reasoning_encrypted_value_event_from_dict = ReasoningEncryptedValueEvent.from_dict(reasoning_encrypted_value_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


