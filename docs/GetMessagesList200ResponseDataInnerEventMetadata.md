# GetMessagesList200ResponseDataInnerEventMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | The updated title. | 
**description** | **str** | The updated description. | [optional] 
**call_id** | **str** | Unique identifier of the call. | [optional] 
**is_video** | **bool** | Indicates whether the call is a video call. | 
**link** | **str** | The invitation link used to join the group. | [optional] 
**start** | **str** | Start date and time of the call in ISO format. | 
**end** | **str** | Expected end date and time of the call in ISO format. | [optional] 
**duration** | **float** | Duration for which the message remains pinned, if applicable. | [optional] 
**message_id** | **str** | ID of the message to which the reaction was added or removed. | 
**is_pin** | **bool** | Indicates whether the message is pinned (true) or unpinned (false). | 
**user_id** | **str** | ID of the participant whose role was updated. | 
**user_name** | **str** | Name of the participant who left or was removed from the group. | [optional] 
**reason** | **str** | Specifies whether the reaction was added or removed. | 
**subject** | **str** | The updated subject. | [optional] 
**reaction** | **str** | The reaction added or removed. | 

## Example

```python
from unipile.models.get_messages_list200_response_data_inner_event_metadata import GetMessagesList200ResponseDataInnerEventMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessagesList200ResponseDataInnerEventMetadata from a JSON string
get_messages_list200_response_data_inner_event_metadata_instance = GetMessagesList200ResponseDataInnerEventMetadata.from_json(json)
# print the JSON string representation of the object
print(GetMessagesList200ResponseDataInnerEventMetadata.to_json())

# convert the object into a dict
get_messages_list200_response_data_inner_event_metadata_dict = get_messages_list200_response_data_inner_event_metadata_instance.to_dict()
# create an instance of GetMessagesList200ResponseDataInnerEventMetadata from a dict
get_messages_list200_response_data_inner_event_metadata_from_dict = GetMessagesList200ResponseDataInnerEventMetadata.from_dict(get_messages_list200_response_data_inner_event_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


