# RawEvent

Event containing a raw event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'RAW']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**event** | **object** |  | 
**source** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.raw_event import RawEvent

# TODO update the JSON string below
json = "{}"
# create an instance of RawEvent from a JSON string
raw_event_instance = RawEvent.from_json(json)
# print the JSON string representation of the object
print(RawEvent.to_json())

# convert the object into a dict
raw_event_dict = raw_event_instance.to_dict()
# create an instance of RawEvent from a dict
raw_event_from_dict = RawEvent.from_dict(raw_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


