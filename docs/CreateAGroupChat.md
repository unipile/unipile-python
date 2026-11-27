# CreateAGroupChat

A new group chat to create in the community.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the community chat to create. | 

## Example

```python
from unipile.models.create_a_group_chat import CreateAGroupChat

# TODO update the JSON string below
json = "{}"
# create an instance of CreateAGroupChat from a JSON string
create_a_group_chat_instance = CreateAGroupChat.from_json(json)
# print the JSON string representation of the object
print(CreateAGroupChat.to_json())

# convert the object into a dict
create_a_group_chat_dict = create_a_group_chat_instance.to_dict()
# create an instance of CreateAGroupChat from a dict
create_a_group_chat_from_dict = CreateAGroupChat.from_dict(create_a_group_chat_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


