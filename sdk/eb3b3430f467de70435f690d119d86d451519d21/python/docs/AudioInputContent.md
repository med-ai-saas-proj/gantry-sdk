# AudioInputContent

An audio input content fragment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'audio']
**source** | [**Source**](Source.md) |  | 
**metadata** | [**AnyOf**](AnyOf.md) |  | [optional] 

## Example

```python
from openapi_client.models.audio_input_content import AudioInputContent

# TODO update the JSON string below
json = "{}"
# create an instance of AudioInputContent from a JSON string
audio_input_content_instance = AudioInputContent.from_json(json)
# print the JSON string representation of the object
print(AudioInputContent.to_json())

# convert the object into a dict
audio_input_content_dict = audio_input_content_instance.to_dict()
# create an instance of AudioInputContent from a dict
audio_input_content_from_dict = AudioInputContent.from_dict(audio_input_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


