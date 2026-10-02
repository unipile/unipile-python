# GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner

The parameters of an external hyperlink contained in the body.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **str** | The URL the link points to. | 
**starts_at** | **float** | The index in the body where the link starts. | 
**length** | **float** | The number of characters in the body that make up the link, starting at the &#x60;starts_at&#x60; index. | 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_last_message_any_of1_hyperlinks_inner import GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner from a JSON string
get_chats_list200_response_data_inner_last_message_any_of1_hyperlinks_inner_instance = GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_last_message_any_of1_hyperlinks_inner_dict = get_chats_list200_response_data_inner_last_message_any_of1_hyperlinks_inner_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner from a dict
get_chats_list200_response_data_inner_last_message_any_of1_hyperlinks_inner_from_dict = GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner.from_dict(get_chats_list200_response_data_inner_last_message_any_of1_hyperlinks_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


