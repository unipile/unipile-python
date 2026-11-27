# StartChatRequestUsersIds

Participant(s) of the chat. To start a 1to1 chat, pass a single user ID as a string, for example `\"users_ids\": \"user_id\"`. To start a group (if supported by the provider), pass an array of user IDs, for example `\"users_ids\": [\"user_id_1\", \"user_id_2\"]`. Passing an array with a single user ID will attempt to start a group with that user only. These formats apply to both Start a Chat and Start a Chat from Inbox.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.start_chat_request_users_ids import StartChatRequestUsersIds

# TODO update the JSON string below
json = "{}"
# create an instance of StartChatRequestUsersIds from a JSON string
start_chat_request_users_ids_instance = StartChatRequestUsersIds.from_json(json)
# print the JSON string representation of the object
print(StartChatRequestUsersIds.to_json())

# convert the object into a dict
start_chat_request_users_ids_dict = start_chat_request_users_ids_instance.to_dict()
# create an instance of StartChatRequestUsersIds from a dict
start_chat_request_users_ids_from_dict = StartChatRequestUsersIds.from_dict(start_chat_request_users_ids_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


