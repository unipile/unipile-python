# GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The text of the question. | 
**is_eliminatory** | **bool** | Whether an unexpected answer is considered a disqualifying factor. | 
**choices** | [**List[GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInnerChoicesInner]**](GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInnerChoicesInner.md) | A list of choices. | 

## Example

```python
from unipile.models.get_recruiter_job_posting_by_project_id200_response_screening_questions_inner import GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner from a JSON string
get_recruiter_job_posting_by_project_id200_response_screening_questions_inner_instance = GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner.to_json())

# convert the object into a dict
get_recruiter_job_posting_by_project_id200_response_screening_questions_inner_dict = get_recruiter_job_posting_by_project_id200_response_screening_questions_inner_instance.to_dict()
# create an instance of GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner from a dict
get_recruiter_job_posting_by_project_id200_response_screening_questions_inner_from_dict = GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner.from_dict(get_recruiter_job_posting_by_project_id200_response_screening_questions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


