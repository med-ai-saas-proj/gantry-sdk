# ReasoningMessageContentEvent

Event containing a piece of reasoning message content.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'REASONING_MESSAGE_CONTENT']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**delta** | **str** |  | 

## Example

```python
from openapi_client.models.reasoning_message_content_event import ReasoningMessageContentEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ReasoningMessageContentEvent from a JSON string
reasoning_message_content_event_instance = ReasoningMessageContentEvent.from_json(json)
# print the JSON string representation of the object
print(ReasoningMessageContentEvent.to_json())

# convert the object into a dict
reasoning_message_content_event_dict = reasoning_message_content_event_instance.to_dict()
# create an instance of ReasoningMessageContentEvent from a dict
reasoning_message_content_event_from_dict = ReasoningMessageContentEvent.from_dict(reasoning_message_content_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


