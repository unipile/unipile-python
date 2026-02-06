# ScheduledCallStarted


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**call_id** | **str** | Unique identifier of the call. | [optional] 
**is_video** | **bool** | Indicates whether the call is a video call. | 
**link** | **str** | The link used to join the call. | [optional] 
**start** | **str** | Start date and time of the call in ISO format. | 
**end** | **str** | Expected end date and time of the call in ISO format. | [optional] 
**duration** | **float** | Duration of the call in seconds | [optional] 

## Example

```python
from unipile.models.scheduled_call_started import ScheduledCallStarted

# TODO update the JSON string below
json = "{}"
# create an instance of ScheduledCallStarted from a JSON string
scheduled_call_started_instance = ScheduledCallStarted.from_json(json)
# print the JSON string representation of the object
print(ScheduledCallStarted.to_json())

# convert the object into a dict
scheduled_call_started_dict = scheduled_call_started_instance.to_dict()
# create an instance of ScheduledCallStarted from a dict
scheduled_call_started_from_dict = ScheduledCallStarted.from_dict(scheduled_call_started_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


