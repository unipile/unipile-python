# CallStarted


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**call_id** | **str** | Unique identifier of the call. | [optional] 
**is_video** | **bool** | Indicates whether the call is a video call. | 
**link** | **str** | The link used to join the call. | [optional] 
**start** | **str** | Start date and time of the call in ISO 8601 format. | [optional] 

## Example

```python
from unipile.models.call_started import CallStarted

# TODO update the JSON string below
json = "{}"
# create an instance of CallStarted from a JSON string
call_started_instance = CallStarted.from_json(json)
# print the JSON string representation of the object
print(CallStarted.to_json())

# convert the object into a dict
call_started_dict = call_started_instance.to_dict()
# create an instance of CallStarted from a dict
call_started_from_dict = CallStarted.from_dict(call_started_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


