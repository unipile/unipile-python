# GetClassicJobPosting200ResponseScreeningQuestionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The text of the question. | 
**is_eliminatory** | **bool** | Whether an answer that does not meet expectations is eliminatory. | 
**choices** | [**List[GetClassicJobPosting200ResponseScreeningQuestionsInnerChoicesInner]**](GetClassicJobPosting200ResponseScreeningQuestionsInnerChoicesInner.md) | A list of choices. | 

## Example

```python
from unipile.models.get_classic_job_posting200_response_screening_questions_inner import GetClassicJobPosting200ResponseScreeningQuestionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicJobPosting200ResponseScreeningQuestionsInner from a JSON string
get_classic_job_posting200_response_screening_questions_inner_instance = GetClassicJobPosting200ResponseScreeningQuestionsInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicJobPosting200ResponseScreeningQuestionsInner.to_json())

# convert the object into a dict
get_classic_job_posting200_response_screening_questions_inner_dict = get_classic_job_posting200_response_screening_questions_inner_instance.to_dict()
# create an instance of GetClassicJobPosting200ResponseScreeningQuestionsInner from a dict
get_classic_job_posting200_response_screening_questions_inner_from_dict = GetClassicJobPosting200ResponseScreeningQuestionsInner.from_dict(get_classic_job_posting200_response_screening_questions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


