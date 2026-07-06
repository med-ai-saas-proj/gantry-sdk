# RunAgentInputWithModelSettings


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**thread_id** | **str** |  | 
**run_id** | **str** |  | 
**parent_run_id** | **str** |  | [optional] 
**state** | **object** |  | 
**messages** | [**List[MessagesInner]**](MessagesInner.md) |  | 
**tools** | [**List[Tool]**](Tool.md) |  | 
**context** | [**List[Context]**](Context.md) |  | 
**forwarded_props** | **object** |  | 
**model_settings** | [**ModelSettingsInput**](ModelSettingsInput.md) |  | [optional] 
**system_prompt** | [**Systemprompt**](Systemprompt.md) |  | [optional] 
**max_turns** | **int** |  | [optional] 
**reserved_tokens** | **int** |  | [optional] 

## Example

```python
from openapi_client.models.run_agent_input_with_model_settings import RunAgentInputWithModelSettings

# TODO update the JSON string below
json = "{}"
# create an instance of RunAgentInputWithModelSettings from a JSON string
run_agent_input_with_model_settings_instance = RunAgentInputWithModelSettings.from_json(json)
# print the JSON string representation of the object
print(RunAgentInputWithModelSettings.to_json())

# convert the object into a dict
run_agent_input_with_model_settings_dict = run_agent_input_with_model_settings_instance.to_dict()
# create an instance of RunAgentInputWithModelSettings from a dict
run_agent_input_with_model_settings_from_dict = RunAgentInputWithModelSettings.from_dict(run_agent_input_with_model_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


