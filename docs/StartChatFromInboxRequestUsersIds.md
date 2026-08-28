# StartChatFromInboxRequestUsersIds

Participant(s) of the chat. To start a 1to1 chat, pass a single user id as a string. To start a group, pass an array of user ids. Passing an array with a single user id will attempt to start a group with that user only.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.start_chat_from_inbox_request_users_ids import StartChatFromInboxRequestUsersIds

# TODO update the JSON string below
json = "{}"
# create an instance of StartChatFromInboxRequestUsersIds from a JSON string
start_chat_from_inbox_request_users_ids_instance = StartChatFromInboxRequestUsersIds.from_json(json)
# print the JSON string representation of the object
print(StartChatFromInboxRequestUsersIds.to_json())

# convert the object into a dict
start_chat_from_inbox_request_users_ids_dict = start_chat_from_inbox_request_users_ids_instance.to_dict()
# create an instance of StartChatFromInboxRequestUsersIds from a dict
start_chat_from_inbox_request_users_ids_from_dict = StartChatFromInboxRequestUsersIds.from_dict(start_chat_from_inbox_request_users_ids_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


