# GetRecruiterPipelineCandidatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**stage_id** | **str** | The pipeline stage ID. Leave undefined to get candidates from all stages.    Native filter : Active stage    | [optional] 
**sort_by** | **str** | The sort method.    Native filter : Sort by    | [optional] 
**spotlights** | **List[str]** | A list of spotlights. | [optional] 
**recruiting_activity** | [**GetRecruiterPipelineCandidatesRequestRecruitingActivity**](GetRecruiterPipelineCandidatesRequestRecruitingActivity.md) |  | [optional] 
**added_by** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SEAT&#x60; type to find out the possible values.    Native filter : Added by    | [optional] 
**skills** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values.    Native filter : Skills    | [optional] 
**years_of_experience** | [**List[GetClassicApplicantsRequestYearsOfExperienceInner]**](GetClassicApplicantsRequestYearsOfExperienceInner.md) |  | [optional] 
**job_title** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values.    Native filter : Job titles    | [optional] 
**company** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;CURRENT_COMPANY&#x60; type to find out the possible values.    Native filter : Current companies    | [optional] 
**location** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values.    Native filter : Current locations    | [optional] 

## Example

```python
from unipile.models.get_recruiter_pipeline_candidates_request import GetRecruiterPipelineCandidatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterPipelineCandidatesRequest from a JSON string
get_recruiter_pipeline_candidates_request_instance = GetRecruiterPipelineCandidatesRequest.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterPipelineCandidatesRequest.to_json())

# convert the object into a dict
get_recruiter_pipeline_candidates_request_dict = get_recruiter_pipeline_candidates_request_instance.to_dict()
# create an instance of GetRecruiterPipelineCandidatesRequest from a dict
get_recruiter_pipeline_candidates_request_from_dict = GetRecruiterPipelineCandidatesRequest.from_dict(get_recruiter_pipeline_candidates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


