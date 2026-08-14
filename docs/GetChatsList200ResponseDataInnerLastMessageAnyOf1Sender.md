# GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender

The user who sent the message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the user for the provider. Usually an internal identifier used by the API only. | 
**object** | **str** |  | 
**type** | **str** | Type of the user       - &#x60;individual&#x60; is an individual user.       - &#x60;organization&#x60; is an organization / business entity.       - &#x60;other&#x60; is an other type of entity. | 
**public_identifier** | **str** | Public identifier of the user for the provider. Usually a shareable tag visible in urls and profiles.  | [optional] 
**display_name** | **str** | Display name of the user as exposed by the provider. | 
**first_name** | **str** | First name of the user. | [optional] 
**last_name** | **str** | Last name of the user. | [optional] 
**profile_url** | **str** | Public url to the profile of the user. | [optional] 
**public_picture_url** | **str** | Public url to the profile picture of the user. | [optional] 
**private_picture_download_url** | **str** | Private url to download the profile picture of the user. This url require authentication. | [optional] 
**description** | **str** | Description of the user. | [optional] 
**specifics** | **object** | Provider-specific user data. | [optional] 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_last_message_any_of1_sender import GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender from a JSON string
get_chats_list200_response_data_inner_last_message_any_of1_sender_instance = GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_last_message_any_of1_sender_dict = get_chats_list200_response_data_inner_last_message_any_of1_sender_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender from a dict
get_chats_list200_response_data_inner_last_message_any_of1_sender_from_dict = GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.from_dict(get_chats_list200_response_data_inner_last_message_any_of1_sender_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


