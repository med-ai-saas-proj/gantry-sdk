# StateSnapshotEvent

Event containing a snapshot of the state.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'STATE_SNAPSHOT']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**snapshot** | **object** |  | 

## Example

```python
from openapi_client.models.state_snapshot_event import StateSnapshotEvent

# TODO update the JSON string below
json = "{}"
# create an instance of StateSnapshotEvent from a JSON string
state_snapshot_event_instance = StateSnapshotEvent.from_json(json)
# print the JSON string representation of the object
print(StateSnapshotEvent.to_json())

# convert the object into a dict
state_snapshot_event_dict = state_snapshot_event_instance.to_dict()
# create an instance of StateSnapshotEvent from a dict
state_snapshot_event_from_dict = StateSnapshotEvent.from_dict(state_snapshot_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


