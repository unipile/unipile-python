# MessagePreview


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the message. | [optional] 
**text** | **str** | The text content of the message. | 
**sender_display_name** | **str** | The display name of the sender of the message. | [optional] 
**is_sender** | **bool** | Is the message sent by the current user. | [optional] 

## Example

```python
from unipile.models.message_preview import MessagePreview

# TODO update the JSON string below
json = "{}"
# create an instance of MessagePreview from a JSON string
message_preview_instance = MessagePreview.from_json(json)
# print the JSON string representation of the object
print(MessagePreview.to_json())

# convert the object into a dict
message_preview_dict = message_preview_instance.to_dict()
# create an instance of MessagePreview from a dict
message_preview_from_dict = MessagePreview.from_dict(message_preview_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


