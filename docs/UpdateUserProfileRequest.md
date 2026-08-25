# UpdateUserProfileRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_name** | **str** | The first name of the User. Updating this field is not supported by LinkedIn. | [optional] 
**last_name** | **str** | The last name of the User. Updating this field is not supported by LinkedIn. | [optional] 
**description** | **str** | Description of the User. Updating this field is not supported by LinkedIn. | [optional] 
**location** | **str** | Location of the User. Omit it to leave it unchanged. | [optional] 
**bio** | **str** | Bio / About section. Omit it to leave it unchanged or use an empty string to clear it. | [optional] 
**picture** | [**SendEmailRequestAttachmentsInner**](SendEmailRequestAttachmentsInner.md) |  | [optional] 
**background_picture** | [**SendEmailRequestAttachmentsInner**](SendEmailRequestAttachmentsInner.md) |  | [optional] 
**specifics** | [**UpdateUserProfileRequestSpecifics**](UpdateUserProfileRequestSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.update_user_profile_request import UpdateUserProfileRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequest from a JSON string
update_user_profile_request_instance = UpdateUserProfileRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequest.to_json())

# convert the object into a dict
update_user_profile_request_dict = update_user_profile_request_instance.to_dict()
# create an instance of UpdateUserProfileRequest from a dict
update_user_profile_request_from_dict = UpdateUserProfileRequest.from_dict(update_user_profile_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


