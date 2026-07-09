# GetChat200ResponseUserSpecifics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**location** | **str** | The geographical location of the user. | [optional] 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | [optional] 
**industry** | **str** | The user&#39;s industry. | [optional] 
**is_following** | **bool** | Whether the current user follows the user. | [optional] 
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
from unipile.models.get_chat200_response_user_specifics import GetChat200ResponseUserSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of GetChat200ResponseUserSpecifics from a JSON string
get_chat200_response_user_specifics_instance = GetChat200ResponseUserSpecifics.from_json(json)
# print the JSON string representation of the object
print(GetChat200ResponseUserSpecifics.to_json())

# convert the object into a dict
get_chat200_response_user_specifics_dict = get_chat200_response_user_specifics_instance.to_dict()
# create an instance of GetChat200ResponseUserSpecifics from a dict
get_chat200_response_user_specifics_from_dict = GetChat200ResponseUserSpecifics.from_dict(get_chat200_response_user_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


