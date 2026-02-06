# CreateClassicJobPostingDraftRequestScreeningQuestionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The question that must be asked. | 
**qualification_required** | **bool** | Whether the applicant should be disqualified if the answer doesn&#39;t match what is expected. | [optional] [default to False]
**answer_type** | **str** |  | 
**min_expectation** | **float** | A minimum expectation. | [optional] 
**max_expectation** | **float** | A maximum expectation. | [optional] 
**suggested_value** | **str** | A suggested value. | 
**choices** | **List[str]** | A list of choices. | 
**expected_choices** | **List[str]** | A list of ideal choices. | 

## Example

```python
from unipile.models.create_classic_job_posting_draft_request_screening_questions_inner import CreateClassicJobPostingDraftRequestScreeningQuestionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of CreateClassicJobPostingDraftRequestScreeningQuestionsInner from a JSON string
create_classic_job_posting_draft_request_screening_questions_inner_instance = CreateClassicJobPostingDraftRequestScreeningQuestionsInner.from_json(json)
# print the JSON string representation of the object
print(CreateClassicJobPostingDraftRequestScreeningQuestionsInner.to_json())

# convert the object into a dict
create_classic_job_posting_draft_request_screening_questions_inner_dict = create_classic_job_posting_draft_request_screening_questions_inner_instance.to_dict()
# create an instance of CreateClassicJobPostingDraftRequestScreeningQuestionsInner from a dict
create_classic_job_posting_draft_request_screening_questions_inner_from_dict = CreateClassicJobPostingDraftRequestScreeningQuestionsInner.from_dict(create_classic_job_posting_draft_request_screening_questions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


