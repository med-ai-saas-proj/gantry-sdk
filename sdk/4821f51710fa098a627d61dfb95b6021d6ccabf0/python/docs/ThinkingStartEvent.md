# ThinkingStartEvent

Event indicating the start of a thinking step event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'THINKING_START']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**title** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.thinking_start_event import ThinkingStartEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ThinkingStartEvent from a JSON string
thinking_start_event_instance = ThinkingStartEvent.from_json(json)
# print the JSON string representation of the object
print(ThinkingStartEvent.to_json())

# convert the object into a dict
thinking_start_event_dict = thinking_start_event_instance.to_dict()
# create an instance of ThinkingStartEvent from a dict
thinking_start_event_from_dict = ThinkingStartEvent.from_dict(thinking_start_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


