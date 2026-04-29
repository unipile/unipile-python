# EditClassicJobPostingRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | [**CreateClassicJobPostingDraftRequestJobTitle**](CreateClassicJobPostingDraftRequestJobTitle.md) |  | [optional] 
**company** | [**CreateClassicJobPostingDraftRequestCompany**](CreateClassicJobPostingDraftRequestCompany.md) |  | [optional] 
**workplace_type** | **str** | The workplace type of the job. | [optional] 
**location** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_LOCATION&#x60; type to find out the possible values. | [optional] 
**employment_status** | **str** | The employment status of the job. | [optional] 
**description** | **str** | The job description. You can use HTML tags to structure your content. | [optional] 
**skills** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values. The skills related to the job posting. | [optional] 
**apply_method** | [**CreateClassicJobPostingDraftRequestApplyMethod**](CreateClassicJobPostingDraftRequestApplyMethod.md) |  | [optional] 
**screening_questions** | [**List[EditClassicJobPostingRequestScreeningQuestionsInner]**](EditClassicJobPostingRequestScreeningQuestionsInner.md) | The questions to be asked to the applicants. | [optional] 
**rejection_settings** | [**CreateClassicJobPostingDraftRequestRejectionSettings**](CreateClassicJobPostingDraftRequestRejectionSettings.md) |  | [optional] 

## Example

```python
from unipile.models.edit_classic_job_posting_request import EditClassicJobPostingRequest

# TODO update the JSON string below
json = "{}"
# create an instance of EditClassicJobPostingRequest from a JSON string
edit_classic_job_posting_request_instance = EditClassicJobPostingRequest.from_json(json)
# print the JSON string representation of the object
print(EditClassicJobPostingRequest.to_json())

# convert the object into a dict
edit_classic_job_posting_request_dict = edit_classic_job_posting_request_instance.to_dict()
# create an instance of EditClassicJobPostingRequest from a dict
edit_classic_job_posting_request_from_dict = EditClassicJobPostingRequest.from_dict(edit_classic_job_posting_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


