# ActivitySnapshotEvent

Event containing a snapshot of an activity message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'ACTIVITY_SNAPSHOT']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**activity_type** | **str** |  | 
**content** | **object** |  | 
**replace** | **bool** |  | [optional] [default to True]

## Example

```python
from openapi_client.models.activity_snapshot_event import ActivitySnapshotEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ActivitySnapshotEvent from a JSON string
activity_snapshot_event_instance = ActivitySnapshotEvent.from_json(json)
# print the JSON string representation of the object
print(ActivitySnapshotEvent.to_json())

# convert the object into a dict
activity_snapshot_event_dict = activity_snapshot_event_instance.to_dict()
# create an instance of ActivitySnapshotEvent from a dict
activity_snapshot_event_from_dict = ActivitySnapshotEvent.from_dict(activity_snapshot_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


