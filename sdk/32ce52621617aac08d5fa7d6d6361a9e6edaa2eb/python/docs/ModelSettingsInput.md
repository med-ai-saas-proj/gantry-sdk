# ModelSettingsInput


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**max_tokens** | **int** |  | [optional] 
**temperature** | **float** |  | [optional] 
**top_p** | **float** |  | [optional] 
**timeout** | **float** |  | [optional] 
**parallel_tool_calls** | **bool** |  | [optional] 
**seed** | **int** |  | [optional] 
**presence_penalty** | **float** |  | [optional] 
**frequency_penalty** | **float** |  | [optional] 
**logit_bias** | **Dict[str, int]** |  | [optional] 
**stop_sequences** | **List[str]** |  | [optional] 
**thinking** | [**Thinking**](Thinking.md) |  | [optional] 
**service_tier** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.model_settings_input import ModelSettingsInput

# TODO update the JSON string below
json = "{}"
# create an instance of ModelSettingsInput from a JSON string
model_settings_input_instance = ModelSettingsInput.from_json(json)
# print the JSON string representation of the object
print(ModelSettingsInput.to_json())

# convert the object into a dict
model_settings_input_dict = model_settings_input_instance.to_dict()
# create an instance of ModelSettingsInput from a dict
model_settings_input_from_dict = ModelSettingsInput.from_dict(model_settings_input_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


