# CustomEvent

Event containing a custom event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'CUSTOM']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**name** | **str** |  | 
**value** | **object** |  | 

## Example

```python
from openapi_client.models.custom_event import CustomEvent

# TODO update the JSON string below
json = "{}"
# create an instance of CustomEvent from a JSON string
custom_event_instance = CustomEvent.from_json(json)
# print the JSON string representation of the object
print(CustomEvent.to_json())

# convert the object into a dict
custom_event_dict = custom_event_instance.to_dict()
# create an instance of CustomEvent from a dict
custom_event_from_dict = CustomEvent.from_dict(custom_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


