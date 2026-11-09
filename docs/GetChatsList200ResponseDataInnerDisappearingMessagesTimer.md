# GetChatsList200ResponseDataInnerDisappearingMessagesTimer

The disappearing-message setting for the conversation: `off` when disabled, `seen` when messages disappear after they are seen, or a retention delay in seconds.     Absent when the provider does not expose the setting.     This describes the retention of the whole conversation, and is distinct from a message `view_mode`, which describes a single piece of content the recipient may only open a limited number of times.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_disappearing_messages_timer import GetChatsList200ResponseDataInnerDisappearingMessagesTimer

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerDisappearingMessagesTimer from a JSON string
get_chats_list200_response_data_inner_disappearing_messages_timer_instance = GetChatsList200ResponseDataInnerDisappearingMessagesTimer.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerDisappearingMessagesTimer.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_disappearing_messages_timer_dict = get_chats_list200_response_data_inner_disappearing_messages_timer_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerDisappearingMessagesTimer from a dict
get_chats_list200_response_data_inner_disappearing_messages_timer_from_dict = GetChatsList200ResponseDataInnerDisappearingMessagesTimer.from_dict(get_chats_list200_response_data_inner_disappearing_messages_timer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


