# GetRecruiterTalentPoolApplyStartersRequest

Filters for people who started applying to a job posting in the project talent pool.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**spotlights** | **List[str]** | A list of spotlights. | [optional] 
**location** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values.    Native filter : Current locations    | [optional] 
**company** | [**GetRecruiterTalentPoolApplyStartersRequestCompany**](GetRecruiterTalentPoolApplyStartersRequestCompany.md) |  | [optional] 
**skills** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values.    Native filter : Skills    | [optional] 
**school** | [**GetRecruiterTalentPoolApplyStartersRequestSchool**](GetRecruiterTalentPoolApplyStartersRequestSchool.md) |  | [optional] 
**industry** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values.    Native filter : Industries    | [optional] 
**job_title** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values.    Native filter : Job titles    | [optional] 
**spoken_language** | [**List[GetRecruiterTalentPoolApplicantsRequestSpokenLanguageInner]**](GetRecruiterTalentPoolApplicantsRequestSpokenLanguageInner.md) | A list of languages. Only available to Recruiter PRO contracts.    Native filter : Spoken languages    | [optional] 
**spoken_language_proficiency** | **str** | The level of proficiency for the spoken languages.    Native filter : Spoken languages proficiency    | [optional] 
**network_distance** | [**List[GetRecruiterTalentPoolApplicantsRequestNetworkDistanceInner]**](GetRecruiterTalentPoolApplicantsRequestNetworkDistanceInner.md) | A list of connection degrees (1 for First, 2 for Second, 3 for Third+ and GROUP for Common group members).    Native filter : Network relationships    | [optional] 
**years_of_experience** | [**GetRecruiterTalentPoolApplicantsRequestYearsOfExperience**](GetRecruiterTalentPoolApplicantsRequestYearsOfExperience.md) |  | [optional] 
**years_in_current_position** | [**GetRecruiterTalentPoolApplicantsRequestYearsInCurrentPosition**](GetRecruiterTalentPoolApplicantsRequestYearsInCurrentPosition.md) |  | [optional] 
**years_in_current_company** | [**GetRecruiterTalentPoolApplicantsRequestYearsInCurrentCompany**](GetRecruiterTalentPoolApplicantsRequestYearsInCurrentCompany.md) |  | [optional] 
**degree** | [**GetRecruiterTalentPoolApplyStartersRequestDegree**](GetRecruiterTalentPoolApplyStartersRequestDegree.md) |  | [optional] 
**field_of_study** | [**GetRecruiterTalentPoolApplyStartersRequestFieldOfStudy**](GetRecruiterTalentPoolApplyStartersRequestFieldOfStudy.md) |  | [optional] 
**seniority** | **List[str]** | A list of experience levels. | [optional] 
**job_function** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_FUNCTION&#x60; type to find out the possible values.    Native filter : Job functions    | [optional] 
**current_company** | [**GetRecruiterTalentPoolApplyStartersRequestCurrentCompany**](GetRecruiterTalentPoolApplyStartersRequestCurrentCompany.md) |  | [optional] 
**company_size** | [**List[GetRecruiterTalentPoolApplicantsRequestCompanySizeInner]**](GetRecruiterTalentPoolApplicantsRequestCompanySizeInner.md) | A list of company size ranges. | [optional] 
**tags** | [**GetRecruiterTalentPoolApplyStartersRequestTags**](GetRecruiterTalentPoolApplyStartersRequestTags.md) |  | [optional] 
**sort_by** | **str** | The sort method.    Native filter : Sort by    | [optional] [default to 'NEWEST_FIRST']

## Example

```python
from unipile.models.get_recruiter_talent_pool_apply_starters_request import GetRecruiterTalentPoolApplyStartersRequest

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterTalentPoolApplyStartersRequest from a JSON string
get_recruiter_talent_pool_apply_starters_request_instance = GetRecruiterTalentPoolApplyStartersRequest.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterTalentPoolApplyStartersRequest.to_json())

# convert the object into a dict
get_recruiter_talent_pool_apply_starters_request_dict = get_recruiter_talent_pool_apply_starters_request_instance.to_dict()
# create an instance of GetRecruiterTalentPoolApplyStartersRequest from a dict
get_recruiter_talent_pool_apply_starters_request_from_dict = GetRecruiterTalentPoolApplyStartersRequest.from_dict(get_recruiter_talent_pool_apply_starters_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


