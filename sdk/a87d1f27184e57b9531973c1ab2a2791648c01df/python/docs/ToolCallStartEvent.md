# ToolCallStartEvent

Event indicating the start of a tool call.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TOOL_CALL_START']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**tool_call_id** | **str** |  | 
**tool_call_name** | **str** |  | 
**parent_message_id** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.tool_call_start_event import ToolCallStartEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ToolCallStartEvent from a JSON string
tool_call_start_event_instance = ToolCallStartEvent.from_json(json)
# print the JSON string representation of the object
print(ToolCallStartEvent.to_json())

# convert the object into a dict
tool_call_start_event_dict = tool_call_start_event_instance.to_dict()
# create an instance of ToolCallStartEvent from a dict
tool_call_start_event_from_dict = ToolCallStartEvent.from_dict(tool_call_start_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


