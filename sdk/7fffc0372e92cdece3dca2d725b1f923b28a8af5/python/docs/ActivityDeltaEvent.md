# ActivityDeltaEvent

Event containing a JSON Patch delta for an activity message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'ACTIVITY_DELTA']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**activity_type** | **str** |  | 
**patch** | **List[object]** |  | 

## Example

```python
from openapi_client.models.activity_delta_event import ActivityDeltaEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ActivityDeltaEvent from a JSON string
activity_delta_event_instance = ActivityDeltaEvent.from_json(json)
# print the JSON string representation of the object
print(ActivityDeltaEvent.to_json())

# convert the object into a dict
activity_delta_event_dict = activity_delta_event_instance.to_dict()
# create an instance of ActivityDeltaEvent from a dict
activity_delta_event_from_dict = ActivityDeltaEvent.from_dict(activity_delta_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


