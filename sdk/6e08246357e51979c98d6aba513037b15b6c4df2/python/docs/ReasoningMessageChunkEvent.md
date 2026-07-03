# ReasoningMessageChunkEvent

Event containing a chunk of reasoning message content.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'REASONING_MESSAGE_CHUNK']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | [optional] 
**delta** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.reasoning_message_chunk_event import ReasoningMessageChunkEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ReasoningMessageChunkEvent from a JSON string
reasoning_message_chunk_event_instance = ReasoningMessageChunkEvent.from_json(json)
# print the JSON string representation of the object
print(ReasoningMessageChunkEvent.to_json())

# convert the object into a dict
reasoning_message_chunk_event_dict = reasoning_message_chunk_event_instance.to_dict()
# create an instance of ReasoningMessageChunkEvent from a dict
reasoning_message_chunk_event_from_dict = ReasoningMessageChunkEvent.from_dict(reasoning_message_chunk_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


