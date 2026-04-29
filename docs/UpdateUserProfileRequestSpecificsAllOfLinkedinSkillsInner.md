# UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The ID of the Company. | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.update_user_profile_request_specifics_all_of_linkedin_skills_inner import UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner from a JSON string
update_user_profile_request_specifics_all_of_linkedin_skills_inner_instance = UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner.to_json())

# convert the object into a dict
update_user_profile_request_specifics_all_of_linkedin_skills_inner_dict = update_user_profile_request_specifics_all_of_linkedin_skills_inner_instance.to_dict()
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner from a dict
update_user_profile_request_specifics_all_of_linkedin_skills_inner_from_dict = UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner.from_dict(update_user_profile_request_specifics_all_of_linkedin_skills_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


