# LinkedIn3Credentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or phone of the LinkedIn account. | 
**password** | **str** | Password of the LinkedIn account. | 
**user_agent** | **str** | The exact user agent of the browser on which the session has been started. You can easily get it in the browser&#39;s console with this command : &#x60;console.log(navigator.userAgent)&#x60; | 
**access_token** | **str** | The access token to authenticate with. This is the &#x60;li_at&#x60; cookie value. | 
**premium_access_token** | **str** | The access token to authenticate Recruiter or Sales Navigator with. This is the &#x60;li_a&#x60; cookie value. | [optional] 

## Example

```python
from unipile.models.linked_in3_credentials import LinkedIn3Credentials

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn3Credentials from a JSON string
linked_in3_credentials_instance = LinkedIn3Credentials.from_json(json)
# print the JSON string representation of the object
print(LinkedIn3Credentials.to_json())

# convert the object into a dict
linked_in3_credentials_dict = linked_in3_credentials_instance.to_dict()
# create an instance of LinkedIn3Credentials from a dict
linked_in3_credentials_from_dict = LinkedIn3Credentials.from_dict(linked_in3_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


