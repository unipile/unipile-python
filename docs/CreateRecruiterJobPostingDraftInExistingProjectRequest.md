# CreateRecruiterJobPostingDraftInExistingProjectRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle**](CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle.md) |  | 
**company** | [**EditClassicJobPostingRequestCompany**](EditClassicJobPostingRequestCompany.md) |  | 
**workplace_type** | **str** | The working method of the job. | 
**location** | **str** |  | 
**employment_status** | **str** | The employment status of the job. | 
**seniority_level** | **str** | The level of experience of the job. | 
**description** | **str** | The job description. You can use HTML tags to structure your content. | 
**industry** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values. The company industries related to the job posting. | 
**job_function** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_FUNCTION&#x60; type to find out the possible values. The job functions related to the job posting. | 
**skills** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values. The skills related to the job posting. | [optional] 
**include_poster_info** | **bool** | Whether basic information about you should be available on the job posting. | [optional] [default to True]
**tracking_pixel_url** | **str** | The tracking pixel URL of the company. | [optional] 
**company_job_id** | **str** | The ID of the job in the company&#39;s system. | [optional] 
**apply_method** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod**](CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod.md) |  | 
**screening_questions** | [**List[EditClassicJobPostingRequestScreeningQuestionsInner]**](EditClassicJobPostingRequestScreeningQuestionsInner.md) | The questions to be asked to the applicants. | [optional] 
**rejection_settings** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings**](CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings.md) |  | [optional] 

## Example

```python
from unipile.models.create_recruiter_job_posting_draft_in_existing_project_request import CreateRecruiterJobPostingDraftInExistingProjectRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequest from a JSON string
create_recruiter_job_posting_draft_in_existing_project_request_instance = CreateRecruiterJobPostingDraftInExistingProjectRequest.from_json(json)
# print the JSON string representation of the object
print(CreateRecruiterJobPostingDraftInExistingProjectRequest.to_json())

# convert the object into a dict
create_recruiter_job_posting_draft_in_existing_project_request_dict = create_recruiter_job_posting_draft_in_existing_project_request_instance.to_dict()
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequest from a dict
create_recruiter_job_posting_draft_in_existing_project_request_from_dict = CreateRecruiterJobPostingDraftInExistingProjectRequest.from_dict(create_recruiter_job_posting_draft_in_existing_project_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


