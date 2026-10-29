# CookieAuthentication2

Use Facebook or Messenger cookies to authenticate with Meta messaging.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**xs** | **str** | The &#x60;xs&#x60; cookie value. | 
**c_user** | **str** | The &#x60;c_user&#x60; cookie value. | 
**datr** | **str** | The &#x60;datr&#x60; cookie value. | 
**sb** | **str** | Optional &#x60;sb&#x60; cookie value. | [optional] 
**fr** | **str** | Optional &#x60;fr&#x60; cookie value. | [optional] 
**wd** | **str** | Optional &#x60;wd&#x60; cookie value. | [optional] 
**presence** | **str** | Optional &#x60;presence&#x60; cookie value. | [optional] 
**oo** | **str** | Optional &#x60;oo&#x60; cookie value. | [optional] 

## Example

```python
from unipile.models.cookie_authentication2 import CookieAuthentication2

# TODO update the JSON string below
json = "{}"
# create an instance of CookieAuthentication2 from a JSON string
cookie_authentication2_instance = CookieAuthentication2.from_json(json)
# print the JSON string representation of the object
print(CookieAuthentication2.to_json())

# convert the object into a dict
cookie_authentication2_dict = cookie_authentication2_instance.to_dict()
# create an instance of CookieAuthentication2 from a dict
cookie_authentication2_from_dict = CookieAuthentication2.from_dict(cookie_authentication2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


