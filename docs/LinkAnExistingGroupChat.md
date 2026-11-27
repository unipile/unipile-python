# LinkAnExistingGroupChat

An existing group chat to link to the community.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | **str** | The ID of an existing group chat of the Messaging API to link to the community. | 

## Example

```python
from unipile.models.link_an_existing_group_chat import LinkAnExistingGroupChat

# TODO update the JSON string below
json = "{}"
# create an instance of LinkAnExistingGroupChat from a JSON string
link_an_existing_group_chat_instance = LinkAnExistingGroupChat.from_json(json)
# print the JSON string representation of the object
print(LinkAnExistingGroupChat.to_json())

# convert the object into a dict
link_an_existing_group_chat_dict = link_an_existing_group_chat_instance.to_dict()
# create an instance of LinkAnExistingGroupChat from a dict
link_an_existing_group_chat_from_dict = LinkAnExistingGroupChat.from_dict(link_an_existing_group_chat_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


