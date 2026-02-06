# GetUserProfile200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the user for the provider. Usually an internal identifier used by the API only. | 
**object** | **str** |  | 
**type** | **str** | Type of the user.       - &#x60;individual&#x60; is an individual user.       - &#x60;organization&#x60; is an organization / business entity.       - &#x60;other&#x60; is an other type of entity. | 
**public_identifier** | **str** | Public identifier of the user for the provider. Usually a shareable tag visible in urls and profiles.  | [optional] 
**display_name** | **str** | Display name of the user. | 
**profile_url** | **str** | Public url to the profile of the user. | [optional] 
**public_picture_url** | **str** | Public url to the profile picture of the user. | [optional] 
**private_picture_download_url** | **str** | Private url to download the profile picture of the user. This url require authentication. | [optional] 
**description** | **str** | Description of the user. | [optional] 
**background_picture_url** | **str** | URL of the user&#39;s background / banner picture. | [optional] 
**public_picture_url_large** | **str** | URL of the user&#39;s public picture in large size. | [optional] 
**first_name** | **str** | First name of the user. | [optional] 
**last_name** | **str** | Last name of the user. | [optional] 
**birth_date** | **str** | Birth date of the user. | [optional] 
**addresses** | **List[str]** |  | [optional] 
**emails** | **List[str]** |  | [optional] 
**phone_numbers** | **List[str]** |  | [optional] 
**created_at** | **str** | Date and time when the user account was created on the provider. | [optional] 
**bio** | **str** | Biography of the user. | [optional] 
**location** | **str** | Location of the user. | [optional] 
**muted_until** | **str** | Date and time until when the user is muted.  | [optional] 
**following** | **bool** | Whether the user is followed by the current user. | [optional] 
**followers_count** | **float** | Number of followers of the user. | [optional] 
**following_count** | **float** | Number of users followed by the user. | [optional] 
**relations_count** | **float** | Number of relations of the user. | [optional] 
**shared_relations_count** | **float** | Number of users that have a relation with the given profile and with the account owner. | [optional] 
**shared_followers_count** | **float** | Number of following users that follows the given profile. | [optional] 
**is_blocked** | **bool** | Whether the user is blocked by the current user. | 
**provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**specifics** | [**GetUserProfile200ResponseSpecifics**](GetUserProfile200ResponseSpecifics.md) |  | 

## Example

```python
from unipile.models.get_user_profile200_response import GetUserProfile200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200Response from a JSON string
get_user_profile200_response_instance = GetUserProfile200Response.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200Response.to_json())

# convert the object into a dict
get_user_profile200_response_dict = get_user_profile200_response_instance.to_dict()
# create an instance of GetUserProfile200Response from a dict
get_user_profile200_response_from_dict = GetUserProfile200Response.from_dict(get_user_profile200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


