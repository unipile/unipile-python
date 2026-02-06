# EditClassicJobPostingRequestScreeningQuestionsInner


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
from unipile.models.edit_classic_job_posting_request_screening_questions_inner import EditClassicJobPostingRequestScreeningQuestionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of EditClassicJobPostingRequestScreeningQuestionsInner from a JSON string
edit_classic_job_posting_request_screening_questions_inner_instance = EditClassicJobPostingRequestScreeningQuestionsInner.from_json(json)
# print the JSON string representation of the object
print(EditClassicJobPostingRequestScreeningQuestionsInner.to_json())

# convert the object into a dict
edit_classic_job_posting_request_screening_questions_inner_dict = edit_classic_job_posting_request_screening_questions_inner_instance.to_dict()
# create an instance of EditClassicJobPostingRequestScreeningQuestionsInner from a dict
edit_classic_job_posting_request_screening_questions_inner_from_dict = EditClassicJobPostingRequestScreeningQuestionsInner.from_dict(edit_classic_job_posting_request_screening_questions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


