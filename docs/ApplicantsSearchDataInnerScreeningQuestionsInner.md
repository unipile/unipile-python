# ApplicantsSearchDataInnerScreeningQuestionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The text of the question. | 
**has_succedeed** | **bool** | Whether the Applicant successfully answered the question. | [optional] 
**is_eliminatory** | **bool** | Whether an unexpected answer is considered a disqualifying factor. | [optional] 
**answers** | **List[str]** | A list of answers given by the Applicant. | 

## Example

```python
from unipile.models.applicants_search_data_inner_screening_questions_inner import ApplicantsSearchDataInnerScreeningQuestionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of ApplicantsSearchDataInnerScreeningQuestionsInner from a JSON string
applicants_search_data_inner_screening_questions_inner_instance = ApplicantsSearchDataInnerScreeningQuestionsInner.from_json(json)
# print the JSON string representation of the object
print(ApplicantsSearchDataInnerScreeningQuestionsInner.to_json())

# convert the object into a dict
applicants_search_data_inner_screening_questions_inner_dict = applicants_search_data_inner_screening_questions_inner_instance.to_dict()
# create an instance of ApplicantsSearchDataInnerScreeningQuestionsInner from a dict
applicants_search_data_inner_screening_questions_inner_from_dict = ApplicantsSearchDataInnerScreeningQuestionsInner.from_dict(applicants_search_data_inner_screening_questions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


