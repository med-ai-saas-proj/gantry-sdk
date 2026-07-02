# ToolCallArgsEvent

Event containing tool call arguments.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TOOL_CALL_ARGS']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**tool_call_id** | **str** |  | 
**delta** | **str** |  | 

## Example

```python
from openapi_client.models.tool_call_args_event import ToolCallArgsEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ToolCallArgsEvent from a JSON string
tool_call_args_event_instance = ToolCallArgsEvent.from_json(json)
# print the JSON string representation of the object
print(ToolCallArgsEvent.to_json())

# convert the object into a dict
tool_call_args_event_dict = tool_call_args_event_instance.to_dict()
# create an instance of ToolCallArgsEvent from a dict
tool_call_args_event_from_dict = ToolCallArgsEvent.from_dict(tool_call_args_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


