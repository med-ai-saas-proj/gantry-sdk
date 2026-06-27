# ToolCallChunkEvent

Event containing a chunk of tool call content.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TOOL_CALL_CHUNK']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**tool_call_id** | **str** |  | [optional] 
**tool_call_name** | **str** |  | [optional] 
**parent_message_id** | **str** |  | [optional] 
**delta** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.tool_call_chunk_event import ToolCallChunkEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ToolCallChunkEvent from a JSON string
tool_call_chunk_event_instance = ToolCallChunkEvent.from_json(json)
# print the JSON string representation of the object
print(ToolCallChunkEvent.to_json())

# convert the object into a dict
tool_call_chunk_event_dict = tool_call_chunk_event_instance.to_dict()
# create an instance of ToolCallChunkEvent from a dict
tool_call_chunk_event_from_dict = ToolCallChunkEvent.from_dict(tool_call_chunk_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


