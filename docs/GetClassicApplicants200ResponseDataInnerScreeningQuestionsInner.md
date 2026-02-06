# GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The text of the question. | 
**has_succedeed** | **bool** | Whether the Applicant successfully answered the question. | 
**is_eliminatory** | **bool** | Whether an unexpected answer is considered a disqualifying factor. | 
**answers** | **List[Optional[str]]** | A list of answers given by the Applicant. | 

## Example

```python
from unipile.models.get_classic_applicants200_response_data_inner_screening_questions_inner import GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner from a JSON string
get_classic_applicants200_response_data_inner_screening_questions_inner_instance = GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner.to_json())

# convert the object into a dict
get_classic_applicants200_response_data_inner_screening_questions_inner_dict = get_classic_applicants200_response_data_inner_screening_questions_inner_instance.to_dict()
# create an instance of GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner from a dict
get_classic_applicants200_response_data_inner_screening_questions_inner_from_dict = GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner.from_dict(get_classic_applicants200_response_data_inner_screening_questions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


