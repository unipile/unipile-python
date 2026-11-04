# CookieAuthentication1

Use the `sessionid` cookie to authenticate with Instagram.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sessionid** | **str** | The sessionid cookie value. | 
**user_agent** | **str** | The exact user agent of the browser on which the session has been started. You can get it in the browser&#39;s console with &#x60;console.log(navigator.userAgent)&#x60;. In Hosted Auth, this is collected automatically from the user&#39;s browser. When reconnecting an Account, the user agent it already uses is kept. | [optional] 

## Example

```python
from unipile.models.cookie_authentication1 import CookieAuthentication1

# TODO update the JSON string below
json = "{}"
# create an instance of CookieAuthentication1 from a JSON string
cookie_authentication1_instance = CookieAuthentication1.from_json(json)
# print the JSON string representation of the object
print(CookieAuthentication1.to_json())

# convert the object into a dict
cookie_authentication1_dict = cookie_authentication1_instance.to_dict()
# create an instance of CookieAuthentication1 from a dict
cookie_authentication1_from_dict = CookieAuthentication1.from_dict(cookie_authentication1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


