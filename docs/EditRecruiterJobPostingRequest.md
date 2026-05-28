# EditRecruiterJobPostingRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle**](CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle.md) |  | [optional] 
**company** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestCompany**](CreateRecruiterJobPostingDraftInExistingProjectRequestCompany.md) |  | [optional] 
**workplace_type** | **str** | The working method of the job. | [optional] 
**location** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_LOCATION&#x60; type to find out the possible values. | [optional] 
**employment_status** | **str** | The employment status of the job. | [optional] 
**seniority_level** | **str** | The level of experience of the job. | [optional] 
**description** | **str** | The job description. You can use HTML tags to structure your content. | [optional] 
**industry** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values. The company industries related to the job posting. | [optional] 
**job_function** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_FUNCTION&#x60; type to find out the possible values. The job functions related to the job posting. | [optional] 
**skills** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values. The skills related to the job posting. | [optional] 
**include_poster_info** | **bool** | Whether basic information about you should be available on the job posting. | [optional] [default to True]
**tracking_pixel_url** | **str** | The tracking pixel URL of the company. | [optional] 
**company_job_id** | **str** | The ID of the job in the company&#39;s system. | [optional] 
**apply_method** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod**](CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod.md) |  | [optional] 
**screening_questions** | [**List[EditClassicJobPostingRequestScreeningQuestionsInner]**](EditClassicJobPostingRequestScreeningQuestionsInner.md) | The questions to be asked to the applicants. | [optional] 
**salary** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestSalary**](CreateRecruiterJobPostingDraftInExistingProjectRequestSalary.md) |  | [optional] 
**additional_compensation** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation**](CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation.md) |  | [optional] 
**rejection_settings** | [**CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings**](CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings.md) |  | [optional] 

## Example

```python
from unipile.models.edit_recruiter_job_posting_request import EditRecruiterJobPostingRequest

# TODO update the JSON string below
json = "{}"
# create an instance of EditRecruiterJobPostingRequest from a JSON string
edit_recruiter_job_posting_request_instance = EditRecruiterJobPostingRequest.from_json(json)
# print the JSON string representation of the object
print(EditRecruiterJobPostingRequest.to_json())

# convert the object into a dict
edit_recruiter_job_posting_request_dict = edit_recruiter_job_posting_request_instance.to_dict()
# create an instance of EditRecruiterJobPostingRequest from a dict
edit_recruiter_job_posting_request_from_dict = EditRecruiterJobPostingRequest.from_dict(edit_recruiter_job_posting_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


