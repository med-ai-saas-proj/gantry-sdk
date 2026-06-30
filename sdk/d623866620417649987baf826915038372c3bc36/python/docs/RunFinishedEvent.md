# RunFinishedEvent

Event indicating that a run has finished.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'RUN_FINISHED']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**thread_id** | **str** |  | 
**run_id** | **str** |  | 
**result** | [**AnyOf**](AnyOf.md) |  | [optional] 

## Example

```python
from openapi_client.models.run_finished_event import RunFinishedEvent

# TODO update the JSON string below
json = "{}"
# create an instance of RunFinishedEvent from a JSON string
run_finished_event_instance = RunFinishedEvent.from_json(json)
# print the JSON string representation of the object
print(RunFinishedEvent.to_json())

# convert the object into a dict
run_finished_event_dict = run_finished_event_instance.to_dict()
# create an instance of RunFinishedEvent from a dict
run_finished_event_from_dict = RunFinishedEvent.from_dict(run_finished_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


