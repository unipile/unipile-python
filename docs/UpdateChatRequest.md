# UpdateChatRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | A custom name for the chat. Some providers allow custom names only on groups. | [optional] 
**muted_until** | [**UpdateChatRequestMutedUntil**](UpdateChatRequestMutedUntil.md) |  | [optional] 
**read_status** | **bool** | Set to &#x60;true&#x60; to mark the chat as read. This is useful when displaying the list of messages in your app. Set to &#x60;false&#x60; to mark the chat as unread. | [optional] 

## Example

```python
from unipile.models.update_chat_request import UpdateChatRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateChatRequest from a JSON string
update_chat_request_instance = UpdateChatRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateChatRequest.to_json())

# convert the object into a dict
update_chat_request_dict = update_chat_request_instance.to_dict()
# create an instance of UpdateChatRequest from a dict
update_chat_request_from_dict = UpdateChatRequest.from_dict(update_chat_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


