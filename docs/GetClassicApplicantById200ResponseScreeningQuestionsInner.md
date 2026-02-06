# GetClassicApplicantById200ResponseScreeningQuestionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The text of the question. | 
**has_succedeed** | **bool** | Whether the Applicant successfully answered the question. | 
**is_eliminatory** | **bool** | Whether an unexpected answer is considered a disqualifying factor. | 
**answers** | **List[str]** | A list of answers given by the Applicant. | 

## Example

```python
from unipile.models.get_classic_applicant_by_id200_response_screening_questions_inner import GetClassicApplicantById200ResponseScreeningQuestionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicantById200ResponseScreeningQuestionsInner from a JSON string
get_classic_applicant_by_id200_response_screening_questions_inner_instance = GetClassicApplicantById200ResponseScreeningQuestionsInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicantById200ResponseScreeningQuestionsInner.to_json())

# convert the object into a dict
get_classic_applicant_by_id200_response_screening_questions_inner_dict = get_classic_applicant_by_id200_response_screening_questions_inner_instance.to_dict()
# create an instance of GetClassicApplicantById200ResponseScreeningQuestionsInner from a dict
get_classic_applicant_by_id200_response_screening_questions_inner_from_dict = GetClassicApplicantById200ResponseScreeningQuestionsInner.from_dict(get_classic_applicant_by_id200_response_screening_questions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


