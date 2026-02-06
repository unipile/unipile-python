# UpdateChatRequestMutedUntil

If supported, the date until which the conversation should be muted. Else `true` to mute the chat for an indefinite time, else `false` to un-mute an already muted chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.update_chat_request_muted_until import UpdateChatRequestMutedUntil

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateChatRequestMutedUntil from a JSON string
update_chat_request_muted_until_instance = UpdateChatRequestMutedUntil.from_json(json)
# print the JSON string representation of the object
print(UpdateChatRequestMutedUntil.to_json())

# convert the object into a dict
update_chat_request_muted_until_dict = update_chat_request_muted_until_instance.to_dict()
# create an instance of UpdateChatRequestMutedUntil from a dict
update_chat_request_muted_until_from_dict = UpdateChatRequestMutedUntil.from_dict(update_chat_request_muted_until_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


