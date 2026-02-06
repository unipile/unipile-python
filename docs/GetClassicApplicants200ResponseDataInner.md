# GetClassicApplicants200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The ID of the Applicant. | 
**messaging_token** | **str** | A mandatory token required to initiate a direct conversation. | 
**applied_at** | **str** | The date on which the Application was submitted. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**viewed_at** | **str** | The date on which the Application was first viewed. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**last_messaged_at** | **str** | The date on which the Applicant was last messaged. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**rating** | **str** | The rating that has been set for the Applicant. | [optional] 
**contact_info** | [**GetClassicApplicants200ResponseDataInnerContactInfo**](GetClassicApplicants200ResponseDataInnerContactInfo.md) |  | [optional] 
**has_resume** | **bool** | Whether the Applicant has a downloadable resume available. | [optional] 
**screening_questions** | [**List[GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner]**](GetClassicApplicants200ResponseDataInnerScreeningQuestionsInner.md) | The responses to the job posting screening questions. | [optional] 
**profile** | [**GetClassicApplicants200ResponseDataInnerProfile**](GetClassicApplicants200ResponseDataInnerProfile.md) |  | 

## Example

```python
from unipile.models.get_classic_applicants200_response_data_inner import GetClassicApplicants200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicants200ResponseDataInner from a JSON string
get_classic_applicants200_response_data_inner_instance = GetClassicApplicants200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicants200ResponseDataInner.to_json())

# convert the object into a dict
get_classic_applicants200_response_data_inner_dict = get_classic_applicants200_response_data_inner_instance.to_dict()
# create an instance of GetClassicApplicants200ResponseDataInner from a dict
get_classic_applicants200_response_data_inner_from_dict = GetClassicApplicants200ResponseDataInner.from_dict(get_classic_applicants200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


