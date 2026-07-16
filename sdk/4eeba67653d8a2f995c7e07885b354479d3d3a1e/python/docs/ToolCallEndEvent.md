# ToolCallEndEvent

Event indicating the end of a tool call.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TOOL_CALL_END']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**tool_call_id** | **str** |  | 

## Example

```python
from openapi_client.models.tool_call_end_event import ToolCallEndEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ToolCallEndEvent from a JSON string
tool_call_end_event_instance = ToolCallEndEvent.from_json(json)
# print the JSON string representation of the object
print(ToolCallEndEvent.to_json())

# convert the object into a dict
tool_call_end_event_dict = tool_call_end_event_instance.to_dict()
# create an instance of ToolCallEndEvent from a dict
tool_call_end_event_from_dict = ToolCallEndEvent.from_dict(tool_call_end_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


