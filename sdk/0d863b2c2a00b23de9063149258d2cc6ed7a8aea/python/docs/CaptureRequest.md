# CaptureRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**real_amount** | [**ScaledAmount**](ScaledAmount.md) |  | 

## Example

```python
from openapi_client.models.capture_request import CaptureRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CaptureRequest from a JSON string
capture_request_instance = CaptureRequest.from_json(json)
# print the JSON string representation of the object
print(CaptureRequest.to_json())

# convert the object into a dict
capture_request_dict = capture_request_instance.to_dict()
# create an instance of CaptureRequest from a dict
capture_request_from_dict = CaptureRequest.from_dict(capture_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


