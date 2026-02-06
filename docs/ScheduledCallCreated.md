# ScheduledCallCreated


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**call_id** | **str** | Unique identifier of the call. | [optional] 
**is_video** | **bool** | Indicates whether the call is a video call. | 
**link** | **str** | The link used to join the call. | [optional] 
**start** | **str** | Expected start date and time of the call in ISO format. | 
**end** | **str** | Expected end date and time of the call in ISO format. | [optional] 
**duration** | **float** | Expected call duration in seconds. | [optional] 

## Example

```python
from unipile.models.scheduled_call_created import ScheduledCallCreated

# TODO update the JSON string below
json = "{}"
# create an instance of ScheduledCallCreated from a JSON string
scheduled_call_created_instance = ScheduledCallCreated.from_json(json)
# print the JSON string representation of the object
print(ScheduledCallCreated.to_json())

# convert the object into a dict
scheduled_call_created_dict = scheduled_call_created_instance.to_dict()
# create an instance of ScheduledCallCreated from a dict
scheduled_call_created_from_dict = ScheduledCallCreated.from_dict(scheduled_call_created_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


