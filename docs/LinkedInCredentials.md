# LinkedInCredentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or phone of the LinkedIn account. | 
**password** | **str** | Password of the LinkedIn account. | 
**access_token** | **str** | The access token to authenticate with. This is the &#x60;li_at&#x60; cookie value. | 
**premium_access_token** | **str** | The access token to authenticate Recruiter or Sales Navigator with. This is the &#x60;li_a&#x60; cookie value. | [optional] 

## Example

```python
from unipile.models.linked_in_credentials import LinkedInCredentials

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInCredentials from a JSON string
linked_in_credentials_instance = LinkedInCredentials.from_json(json)
# print the JSON string representation of the object
print(LinkedInCredentials.to_json())

# convert the object into a dict
linked_in_credentials_dict = linked_in_credentials_instance.to_dict()
# create an instance of LinkedInCredentials from a dict
linked_in_credentials_from_dict = LinkedInCredentials.from_dict(linked_in_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


