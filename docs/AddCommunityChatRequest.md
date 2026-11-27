# AddCommunityChatRequest

Link an existing group chat (`chat_id`), or create a group chat (`name`).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | **str** | The ID of an existing group chat of the Messaging API to link to the community. | 
**name** | **str** | The name of the community chat to create. | 

## Example

```python
from unipile.models.add_community_chat_request import AddCommunityChatRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AddCommunityChatRequest from a JSON string
add_community_chat_request_instance = AddCommunityChatRequest.from_json(json)
# print the JSON string representation of the object
print(AddCommunityChatRequest.to_json())

# convert the object into a dict
add_community_chat_request_dict = add_community_chat_request_instance.to_dict()
# create an instance of AddCommunityChatRequest from a dict
add_community_chat_request_from_dict = AddCommunityChatRequest.from_dict(add_community_chat_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


