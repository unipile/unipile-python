# Facebook

Start the authentication intent with the Facebook provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**user_agent** | **str** | The exact user agent of the browser used to retrieve the cookies. You can get it in the browser&#39;s console with &#x60;console.log(navigator.userAgent)&#x60;. In Hosted Auth, this is collected automatically from the user&#39;s browser. When reconnecting an Account, the user agent it already uses is kept. | [optional] 
**credentials** | [**FacebookCredentials**](FacebookCredentials.md) |  | 
**config** | [**FacebookConfig**](FacebookConfig.md) |  | [optional] 

## Example

```python
from unipile.models.facebook import Facebook

# TODO update the JSON string below
json = "{}"
# create an instance of Facebook from a JSON string
facebook_instance = Facebook.from_json(json)
# print the JSON string representation of the object
print(Facebook.to_json())

# convert the object into a dict
facebook_dict = facebook_instance.to_dict()
# create an instance of Facebook from a dict
facebook_from_dict = Facebook.from_dict(facebook_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


