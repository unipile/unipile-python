# GetUserReactionsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**value** | **str** | Value of the reaction. Usually an emoji unicode. | 
**sender** | [**GetMessageReactionsList200ResponseDataInnerSender**](GetMessageReactionsList200ResponseDataInnerSender.md) |  | 
**is_sender** | **bool** | Is the current user the sender of the reaction. | 
**parent_post** | [**GetUserCommentsList200ResponseDataInnerParentPost**](GetUserCommentsList200ResponseDataInnerParentPost.md) |  | [optional] 

## Example

```python
from unipile.models.get_user_reactions_list200_response_data_inner import GetUserReactionsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserReactionsList200ResponseDataInner from a JSON string
get_user_reactions_list200_response_data_inner_instance = GetUserReactionsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetUserReactionsList200ResponseDataInner.to_json())

# convert the object into a dict
get_user_reactions_list200_response_data_inner_dict = get_user_reactions_list200_response_data_inner_instance.to_dict()
# create an instance of GetUserReactionsList200ResponseDataInner from a dict
get_user_reactions_list200_response_data_inner_from_dict = GetUserReactionsList200ResponseDataInner.from_dict(get_user_reactions_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


