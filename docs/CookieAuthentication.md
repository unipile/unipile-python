# CookieAuthentication

Use the `li_at` and `li_a` cookies to authenticate with LinkedIn.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_token** | **str** | The access token to authenticate with. This is the &#x60;li_at&#x60; cookie value. | 
**premium_access_token** | **str** | The access token to authenticate Recruiter or Sales Navigator with. This is the &#x60;li_a&#x60; cookie value. | [optional] 
**user_agent** | **str** | The exact user agent of the browser on which the session has been started. You can easily get it in the browser&#39;s console with this command : &#x60;console.log(navigator.userAgent)&#x60; | 

## Example

```python
from unipile.models.cookie_authentication import CookieAuthentication

# TODO update the JSON string below
json = "{}"
# create an instance of CookieAuthentication from a JSON string
cookie_authentication_instance = CookieAuthentication.from_json(json)
# print the JSON string representation of the object
print(CookieAuthentication.to_json())

# convert the object into a dict
cookie_authentication_dict = cookie_authentication_instance.to_dict()
# create an instance of CookieAuthentication from a dict
cookie_authentication_from_dict = CookieAuthentication.from_dict(cookie_authentication_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


