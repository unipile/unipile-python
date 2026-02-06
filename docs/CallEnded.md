# CallEnded


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**call_id** | **str** | Unique identifier of the call. | [optional] 
**is_video** | **bool** | Indicates whether the call is a video call. | 
**link** | **str** | The link used to join the call. | [optional] 
**start** | **str** | Start date and time of the call in ISO format. | [optional] 
**end** | **str** | End date and time of the call in ISO format. | [optional] 
**duration** | **float** | Duration of the call in seconds (if available). | [optional] 

## Example

```python
from unipile.models.call_ended import CallEnded

# TODO update the JSON string below
json = "{}"
# create an instance of CallEnded from a JSON string
call_ended_instance = CallEnded.from_json(json)
# print the JSON string representation of the object
print(CallEnded.to_json())

# convert the object into a dict
call_ended_dict = call_ended_instance.to_dict()
# create an instance of CallEnded from a dict
call_ended_from_dict = CallEnded.from_dict(call_ended_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


