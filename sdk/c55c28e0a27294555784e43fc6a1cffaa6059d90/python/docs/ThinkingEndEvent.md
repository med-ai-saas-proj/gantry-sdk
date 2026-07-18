# ThinkingEndEvent

Event indicating the end of a thinking step event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'THINKING_END']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 

## Example

```python
from openapi_client.models.thinking_end_event import ThinkingEndEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ThinkingEndEvent from a JSON string
thinking_end_event_instance = ThinkingEndEvent.from_json(json)
# print the JSON string representation of the object
print(ThinkingEndEvent.to_json())

# convert the object into a dict
thinking_end_event_dict = thinking_end_event_instance.to_dict()
# create an instance of ThinkingEndEvent from a dict
thinking_end_event_from_dict = ThinkingEndEvent.from_dict(thinking_end_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


