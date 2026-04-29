# CreateClassicJobPostingDraftRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | [**CreateClassicJobPostingDraftRequestJobTitle**](CreateClassicJobPostingDraftRequestJobTitle.md) |  | 
**company** | [**CreateClassicJobPostingDraftRequestCompany**](CreateClassicJobPostingDraftRequestCompany.md) |  | 
**workplace_type** | **str** | The workplace type of the job. | 
**location** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_LOCATION&#x60; type to find out the possible values. | 
**employment_status** | **str** | The employment status of the job. | 
**description** | **str** | The job description. You can use HTML tags to structure your content. | 
**skills** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values. The skills related to the job posting. | [optional] 
**apply_method** | [**CreateClassicJobPostingDraftRequestApplyMethod**](CreateClassicJobPostingDraftRequestApplyMethod.md) |  | 
**screening_questions** | [**List[CreateClassicJobPostingDraftRequestScreeningQuestionsInner]**](CreateClassicJobPostingDraftRequestScreeningQuestionsInner.md) | The questions to be asked to the applicants. | [optional] 
**rejection_settings** | [**CreateClassicJobPostingDraftRequestRejectionSettings**](CreateClassicJobPostingDraftRequestRejectionSettings.md) |  | [optional] 

## Example

```python
from unipile.models.create_classic_job_posting_draft_request import CreateClassicJobPostingDraftRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateClassicJobPostingDraftRequest from a JSON string
create_classic_job_posting_draft_request_instance = CreateClassicJobPostingDraftRequest.from_json(json)
# print the JSON string representation of the object
print(CreateClassicJobPostingDraftRequest.to_json())

# convert the object into a dict
create_classic_job_posting_draft_request_dict = create_classic_job_posting_draft_request_instance.to_dict()
# create an instance of CreateClassicJobPostingDraftRequest from a dict
create_classic_job_posting_draft_request_from_dict = CreateClassicJobPostingDraftRequest.from_dict(create_classic_job_posting_draft_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


