# GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the user for the provider. Usually an internal identifier used by the API only. | 
**object** | **str** |  | 
**type** | **str** | Type of the user       - &#x60;individual&#x60; is an individual user.       - &#x60;organization&#x60; is an organization / business entity.       - &#x60;other&#x60; is an other type of entity. | 
**public_identifier** | **str** | Public identifier of the user for the provider. Usually a shareable tag visible in urls and profiles.  | [optional] 
**display_name** | **str** | Display name of the user. | 
**profile_url** | **str** | Public url to the profile of the user. | [optional] 
**public_picture_url** | **str** | Public url to the profile picture of the user. | [optional] 
**private_picture_download_url** | **str** | Private url to download the profile picture of the user. This url require authentication. | [optional] 
**description** | **str** | Description of the user. | [optional] 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_projects_inner_contributors_inner import GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner from a JSON string
get_user_profile200_response_specifics_all_of_any_of_projects_inner_contributors_inner_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_projects_inner_contributors_inner_dict = get_user_profile200_response_specifics_all_of_any_of_projects_inner_contributors_inner_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner from a dict
get_user_profile200_response_specifics_all_of_any_of_projects_inner_contributors_inner_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner.from_dict(get_user_profile200_response_specifics_all_of_any_of_projects_inner_contributors_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


