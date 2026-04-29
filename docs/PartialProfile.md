# PartialProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the user. | 
**headline** | **str** | The headline of the User. | 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**location** | **str** | The location of the User. | 
**can_send_inmail** | **bool** | Whether it is possible to send an inMail to this User. | [optional] 
**visibility** | **str** | Indidates that you don&#39;t have access to the full profile of this User. | 
**candidate_id** | **str** | The candidate ID of the User. | 
**is_hidden_candidate** | **bool** | Whether the User has been set as hidden candidate. | 
**hiring_project** | [**PartialProfileHiringProject**](PartialProfileHiringProject.md) |  | [optional] 
**work_experience** | [**List[PartialProfileWorkExperienceInner]**](PartialProfileWorkExperienceInner.md) | A list of the User&#39;s work experiences. | 

## Example

```python
from unipile.models.partial_profile import PartialProfile

# TODO update the JSON string below
json = "{}"
# create an instance of PartialProfile from a JSON string
partial_profile_instance = PartialProfile.from_json(json)
# print the JSON string representation of the object
print(PartialProfile.to_json())

# convert the object into a dict
partial_profile_dict = partial_profile_instance.to_dict()
# create an instance of PartialProfile from a dict
partial_profile_from_dict = PartialProfile.from_dict(partial_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


