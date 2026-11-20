# MessageEventMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | ID of the participant whose role was updated. | 
**user_name** | **str** | Name of the participant who left or was removed from the group. | [optional] 
**reason** | **str** | Specifies whether the reaction was added or removed. | 
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
**subject** | **str** | The updated subject. | [optional] 
**reaction** | **str** | The reaction added or removed. | 

## Example

```python
from unipile.models.message_event_metadata import MessageEventMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of MessageEventMetadata from a JSON string
message_event_metadata_instance = MessageEventMetadata.from_json(json)
# print the JSON string representation of the object
print(MessageEventMetadata.to_json())

# convert the object into a dict
message_event_metadata_dict = message_event_metadata_instance.to_dict()
# create an instance of MessageEventMetadata from a dict
message_event_metadata_from_dict = MessageEventMetadata.from_dict(message_event_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


