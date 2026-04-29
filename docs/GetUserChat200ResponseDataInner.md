# GetUserChat200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | **str** | The ID of the Chat associated with the given user. | 
**inbox_id** | **str** | The ID of the Inbox containing the chat, if applicable. | [optional] 
**has_history** | **bool** | Whether the provider could determine that the chat already contains message history. | [optional] 

## Example

```python
from unipile.models.get_user_chat200_response_data_inner import GetUserChat200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserChat200ResponseDataInner from a JSON string
get_user_chat200_response_data_inner_instance = GetUserChat200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetUserChat200ResponseDataInner.to_json())

# convert the object into a dict
get_user_chat200_response_data_inner_dict = get_user_chat200_response_data_inner_instance.to_dict()
# create an instance of GetUserChat200ResponseDataInner from a dict
get_user_chat200_response_data_inner_from_dict = GetUserChat200ResponseDataInner.from_dict(get_user_chat200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


