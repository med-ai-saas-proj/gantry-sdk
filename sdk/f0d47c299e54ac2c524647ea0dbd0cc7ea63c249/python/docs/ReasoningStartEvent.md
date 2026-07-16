# ReasoningStartEvent

Event indicating the start of a reasoning phase.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'REASONING_START']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 

## Example

```python
from openapi_client.models.reasoning_start_event import ReasoningStartEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ReasoningStartEvent from a JSON string
reasoning_start_event_instance = ReasoningStartEvent.from_json(json)
# print the JSON string representation of the object
print(ReasoningStartEvent.to_json())

# convert the object into a dict
reasoning_start_event_dict = reasoning_start_event_instance.to_dict()
# create an instance of ReasoningStartEvent from a dict
reasoning_start_event_from_dict = ReasoningStartEvent.from_dict(reasoning_start_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


