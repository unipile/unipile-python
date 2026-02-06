# UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**filter** | **str** | A visual filter to be applied to the picture. | [optional] 
**layout** | **object** |  | [optional] 
**contrast** | **float** | The level of contrast. | [optional] 
**vignette** | **float** | The level of vignetting. | [optional] 
**saturation** | **float** | The level of saturation. | [optional] 
**brightness** | **float** | The level of brightness. | [optional] 

## Example

```python
from unipile.models.update_user_profile_request_specifics_all_of_linkedin_picture_options import UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions from a JSON string
update_user_profile_request_specifics_all_of_linkedin_picture_options_instance = UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions.to_json())

# convert the object into a dict
update_user_profile_request_specifics_all_of_linkedin_picture_options_dict = update_user_profile_request_specifics_all_of_linkedin_picture_options_instance.to_dict()
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions from a dict
update_user_profile_request_specifics_all_of_linkedin_picture_options_from_dict = UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions.from_dict(update_user_profile_request_specifics_all_of_linkedin_picture_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


