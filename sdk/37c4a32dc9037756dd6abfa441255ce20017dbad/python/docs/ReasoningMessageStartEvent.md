# ReasoningMessageStartEvent

Event indicating the start of a reasoning message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'REASONING_MESSAGE_START']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**role** | **str** |  | 

## Example

```python
from openapi_client.models.reasoning_message_start_event import ReasoningMessageStartEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ReasoningMessageStartEvent from a JSON string
reasoning_message_start_event_instance = ReasoningMessageStartEvent.from_json(json)
# print the JSON string representation of the object
print(ReasoningMessageStartEvent.to_json())

# convert the object into a dict
reasoning_message_start_event_dict = reasoning_message_start_event_instance.to_dict()
# create an instance of ReasoningMessageStartEvent from a dict
reasoning_message_start_event_from_dict = ReasoningMessageStartEvent.from_dict(reasoning_message_start_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


