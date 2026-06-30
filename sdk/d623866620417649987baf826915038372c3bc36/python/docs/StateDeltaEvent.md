# StateDeltaEvent

Event containing a delta of the state.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'STATE_DELTA']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**delta** | **List[object]** |  | 

## Example

```python
from openapi_client.models.state_delta_event import StateDeltaEvent

# TODO update the JSON string below
json = "{}"
# create an instance of StateDeltaEvent from a JSON string
state_delta_event_instance = StateDeltaEvent.from_json(json)
# print the JSON string representation of the object
print(StateDeltaEvent.to_json())

# convert the object into a dict
state_delta_event_dict = state_delta_event_instance.to_dict()
# create an instance of StateDeltaEvent from a dict
state_delta_event_from_dict = StateDeltaEvent.from_dict(state_delta_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


