# ReasoningEndEvent

Event indicating the end of a reasoning phase.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'REASONING_END']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 

## Example

```python
from openapi_client.models.reasoning_end_event import ReasoningEndEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ReasoningEndEvent from a JSON string
reasoning_end_event_instance = ReasoningEndEvent.from_json(json)
# print the JSON string representation of the object
print(ReasoningEndEvent.to_json())

# convert the object into a dict
reasoning_end_event_dict = reasoning_end_event_instance.to_dict()
# create an instance of ReasoningEndEvent from a dict
reasoning_end_event_from_dict = ReasoningEndEvent.from_dict(reasoning_end_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


