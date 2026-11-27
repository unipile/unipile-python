# JoinChatRequest

The invitation to join a group conversation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invite_code** | **str** | The invitation code or link to the conversation. | 

## Example

```python
from unipile.models.join_chat_request import JoinChatRequest

# TODO update the JSON string below
json = "{}"
# create an instance of JoinChatRequest from a JSON string
join_chat_request_instance = JoinChatRequest.from_json(json)
# print the JSON string representation of the object
print(JoinChatRequest.to_json())

# convert the object into a dict
join_chat_request_dict = join_chat_request_instance.to_dict()
# create an instance of JoinChatRequest from a dict
join_chat_request_from_dict = JoinChatRequest.from_dict(join_chat_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


