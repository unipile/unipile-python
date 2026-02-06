# GetRecruiterTalentPoolApplicantsRequestFieldOfStudy

    Native filter : Fields of study   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;FIELD_OF_STUDY&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;FIELD_OF_STUDY&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.get_recruiter_talent_pool_applicants_request_field_of_study import GetRecruiterTalentPoolApplicantsRequestFieldOfStudy

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterTalentPoolApplicantsRequestFieldOfStudy from a JSON string
get_recruiter_talent_pool_applicants_request_field_of_study_instance = GetRecruiterTalentPoolApplicantsRequestFieldOfStudy.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterTalentPoolApplicantsRequestFieldOfStudy.to_json())

# convert the object into a dict
get_recruiter_talent_pool_applicants_request_field_of_study_dict = get_recruiter_talent_pool_applicants_request_field_of_study_instance.to_dict()
# create an instance of GetRecruiterTalentPoolApplicantsRequestFieldOfStudy from a dict
get_recruiter_talent_pool_applicants_request_field_of_study_from_dict = GetRecruiterTalentPoolApplicantsRequestFieldOfStudy.from_dict(get_recruiter_talent_pool_applicants_request_field_of_study_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


