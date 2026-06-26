# GetChatsList200ResponseDataInnerUserSpecifics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**location** | **str** | The geographical location of the user. | [optional] 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | [optional] 
**industry** | **str** | The user&#39;s industry. | [optional] 
**following** | **bool** | Whether the user is followed by the current user. | [optional] 
**followers_count** | **float** | The number of followers of the user. | [optional] 
**relations_count** | **float** | The number of relations of the user. | [optional] 
**shared_relations_count** | **float** | The number of relations that you share with the user. | [optional] 
**website_url** | **str** | The URL of the website provided by the user. | [optional] 
**portfolio_url** | **str** | The URL of the portfolio provided by the user. | [optional] 
**services_page_url** | **str** | The LinkedIn internal URL of the user&#39;s services page. | [optional] 
**is_premium** | **bool** | Whether the User has a premium account. | [optional] 
**is_verified** | **bool** | Whether the User has a verified account. | [optional] 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_user_specifics import GetChatsList200ResponseDataInnerUserSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerUserSpecifics from a JSON string
get_chats_list200_response_data_inner_user_specifics_instance = GetChatsList200ResponseDataInnerUserSpecifics.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerUserSpecifics.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_user_specifics_dict = get_chats_list200_response_data_inner_user_specifics_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerUserSpecifics from a dict
get_chats_list200_response_data_inner_user_specifics_from_dict = GetChatsList200ResponseDataInnerUserSpecifics.from_dict(get_chats_list200_response_data_inner_user_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


