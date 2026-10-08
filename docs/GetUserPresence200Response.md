# GetUserPresence200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**user_id** | **str** | The ID of the User this presence belongs to. | 
**presence** | **str** | Whether the user is currently connected to the provider.     - &#x60;online&#x60; if the user is connected right now.     - &#x60;offline&#x60; if the user is not connected. &#x60;last_online_at&#x60; is set when the provider exposes the exact date.     - &#x60;unknown&#x60; if the provider reports no presence for this user, which usually means the user hides it. | 
**last_online_at** | **str** | Date and time when the user was last online. Only set when the user is offline and the provider exposes the exact date. | [optional] 
**provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 

## Example

```python
from unipile.models.get_user_presence200_response import GetUserPresence200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserPresence200Response from a JSON string
get_user_presence200_response_instance = GetUserPresence200Response.from_json(json)
# print the JSON string representation of the object
print(GetUserPresence200Response.to_json())

# convert the object into a dict
get_user_presence200_response_dict = get_user_presence200_response_instance.to_dict()
# create an instance of GetUserPresence200Response from a dict
get_user_presence200_response_from_dict = GetUserPresence200Response.from_dict(get_user_presence200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


