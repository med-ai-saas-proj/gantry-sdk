# RunStartedEvent

Event indicating that a run has started.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'RUN_STARTED']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**thread_id** | **str** |  | 
**run_id** | **str** |  | 
**parent_run_id** | **str** |  | [optional] 
**input** | [**RunAgentInput**](RunAgentInput.md) |  | [optional] 

## Example

```python
from openapi_client.models.run_started_event import RunStartedEvent

# TODO update the JSON string below
json = "{}"
# create an instance of RunStartedEvent from a JSON string
run_started_event_instance = RunStartedEvent.from_json(json)
# print the JSON string representation of the object
print(RunStartedEvent.to_json())

# convert the object into a dict
run_started_event_dict = run_started_event_instance.to_dict()
# create an instance of RunStartedEvent from a dict
run_started_event_from_dict = RunStartedEvent.from_dict(run_started_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


