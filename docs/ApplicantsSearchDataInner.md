# ApplicantsSearchDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The ID of the Applicant. | 
**applied_at** | **str** | The date on which the Application was submitted. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**has_resume** | **bool** | Whether the Applicant has a downloadable resume available. | [optional] 
**screening_questions** | [**List[GetClassicApplicantById200ResponseScreeningQuestionsInner]**](GetClassicApplicantById200ResponseScreeningQuestionsInner.md) | The responses to the job posting screening questions. | [optional] 
**profile** | [**ApplicantsSearchDataInnerProfile**](ApplicantsSearchDataInnerProfile.md) |  | 

## Example

```python
from unipile.models.applicants_search_data_inner import ApplicantsSearchDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of ApplicantsSearchDataInner from a JSON string
applicants_search_data_inner_instance = ApplicantsSearchDataInner.from_json(json)
# print the JSON string representation of the object
print(ApplicantsSearchDataInner.to_json())

# convert the object into a dict
applicants_search_data_inner_dict = applicants_search_data_inner_instance.to_dict()
# create an instance of ApplicantsSearchDataInner from a dict
applicants_search_data_inner_from_dict = ApplicantsSearchDataInner.from_dict(applicants_search_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


