# LinkedIn

Start the authentication intent with LinkedIn provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**user_agent** | **str** | If encountering disconnection issues, enter the exact user agent of the browser on which the account has been connected before the &#x60;li_at&#x60; retrieval. You can easily get it in the browser&#39;s console with this command : &#x60;console.log(navigator.userAgent)&#x60; | [optional] 
**user_timezone** | **str** | The time zone of the current user can be used on a few specific features (e.g. scheduled actions). Setting it at authentication avoids having to do it on a case-by-case basis later on. | [optional] 
**credentials** | [**LinkedInCredentials**](LinkedInCredentials.md) |  | 
**config** | [**LinkedInConfig**](LinkedInConfig.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in import LinkedIn

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn from a JSON string
linked_in_instance = LinkedIn.from_json(json)
# print the JSON string representation of the object
print(LinkedIn.to_json())

# convert the object into a dict
linked_in_dict = linked_in_instance.to_dict()
# create an instance of LinkedIn from a dict
linked_in_from_dict = LinkedIn.from_dict(linked_in_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


