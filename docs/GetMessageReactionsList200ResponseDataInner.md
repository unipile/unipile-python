# GetMessageReactionsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**value** | **str** | Value of the reaction. Usually an emoji unicode. | 
**sender** | [**GetMessageReactionsList200ResponseDataInnerSender**](GetMessageReactionsList200ResponseDataInnerSender.md) |  | 
**is_sender** | **bool** | Is the current user the sender of the reaction. | 

## Example

```python
from unipile.models.get_message_reactions_list200_response_data_inner import GetMessageReactionsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessageReactionsList200ResponseDataInner from a JSON string
get_message_reactions_list200_response_data_inner_instance = GetMessageReactionsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetMessageReactionsList200ResponseDataInner.to_json())

# convert the object into a dict
get_message_reactions_list200_response_data_inner_dict = get_message_reactions_list200_response_data_inner_instance.to_dict()
# create an instance of GetMessageReactionsList200ResponseDataInner from a dict
get_message_reactions_list200_response_data_inner_from_dict = GetMessageReactionsList200ResponseDataInner.from_dict(get_message_reactions_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


