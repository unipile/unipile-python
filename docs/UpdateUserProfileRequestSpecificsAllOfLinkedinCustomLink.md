# UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The type of link. | 
**url** | **str** | The URL of the link. | 
**display_on** | **str** | Whether the link should be displayed everywhere or only on the profile. | [optional] [default to 'EVERYWHERE']

## Example

```python
from unipile.models.update_user_profile_request_specifics_all_of_linkedin_custom_link import UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink from a JSON string
update_user_profile_request_specifics_all_of_linkedin_custom_link_instance = UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink.to_json())

# convert the object into a dict
update_user_profile_request_specifics_all_of_linkedin_custom_link_dict = update_user_profile_request_specifics_all_of_linkedin_custom_link_instance.to_dict()
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink from a dict
update_user_profile_request_specifics_all_of_linkedin_custom_link_from_dict = UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink.from_dict(update_user_profile_request_specifics_all_of_linkedin_custom_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


