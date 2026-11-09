# UpdateChatRequestDisappearingMessagesTimer

If supported, set to `off` to disable disappearing messages, `seen` to make messages disappear after they are seen, or provide the retention delay in seconds.     Accepted values by provider:     - WhatsApp: `off`, `86400` (24 hours), `604800` (7 days), `7776000` (90 days).     - Telegram: `off`, `86400` (24 hours), `604800` (7 days), `2678400` (31 days).     - Instagram and LinkedIn: updating this setting is not supported.     The `seen` mode is not currently supported by any provider for this operation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.update_chat_request_disappearing_messages_timer import UpdateChatRequestDisappearingMessagesTimer

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateChatRequestDisappearingMessagesTimer from a JSON string
update_chat_request_disappearing_messages_timer_instance = UpdateChatRequestDisappearingMessagesTimer.from_json(json)
# print the JSON string representation of the object
print(UpdateChatRequestDisappearingMessagesTimer.to_json())

# convert the object into a dict
update_chat_request_disappearing_messages_timer_dict = update_chat_request_disappearing_messages_timer_instance.to_dict()
# create an instance of UpdateChatRequestDisappearingMessagesTimer from a dict
update_chat_request_disappearing_messages_timer_from_dict = UpdateChatRequestDisappearingMessagesTimer.from_dict(update_chat_request_disappearing_messages_timer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


