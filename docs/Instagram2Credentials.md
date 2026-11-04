# Instagram2Credentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or phone of the LinkedIn account. | 
**password** | **str** | Password of the LinkedIn account. | 
**user_agent** | **str** | The exact user agent of the browser on which the session has been started. You can get it in the browser&#39;s console with &#x60;console.log(navigator.userAgent)&#x60;. In Hosted Auth, this is collected automatically from the user&#39;s browser. When reconnecting an Account, the user agent it already uses is kept. | [optional] 
**sessionid** | **str** | The sessionid cookie value. | 

## Example

```python
from unipile.models.instagram2_credentials import Instagram2Credentials

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram2Credentials from a JSON string
instagram2_credentials_instance = Instagram2Credentials.from_json(json)
# print the JSON string representation of the object
print(Instagram2Credentials.to_json())

# convert the object into a dict
instagram2_credentials_dict = instagram2_credentials_instance.to_dict()
# create an instance of Instagram2Credentials from a dict
instagram2_credentials_from_dict = Instagram2Credentials.from_dict(instagram2_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


