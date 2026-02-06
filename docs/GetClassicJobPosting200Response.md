# GetClassicJobPosting200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The ID of the Job posting. | 
**title** | **str** | The title of the Job posting. | 
**company** | [**GetClassicJobPosting200ResponseCompany**](GetClassicJobPosting200ResponseCompany.md) |  | 
**location** | **str** | The location of the Job posting. | 
**state** | **str** | The state of the Job posting. | 
**workplace_type** | **str** | The type of workplace of the Job posting. | [optional] 
**is_repost** | **bool** | Whether the Job posting is a repost. | 
**is_application_limit_reached** | **bool** | Whether the Job posting has reached the maximum number of applications. | 
**industries** | **List[Optional[str]]** | The industries associated with the Job posting. | 
**employment_status** | **str** | The employment status of the Job posting. | [optional] 
**created_at** | **str** | The date on which the Job posting was created. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**published_at** | **str** | The date on which the Job posting was published. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**expires_at** | **str** | The date on which the Job posting will expire. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**closed_at** | **str** | The date on which the Job posting was closed. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**description** | **str** | The description of the Job posting. | 
**budget** | [**GetClassicJobPosting200ResponseBudget**](GetClassicJobPosting200ResponseBudget.md) |  | [optional] 
**views_count** | **float** | The number of visits to this Job posting. | 
**applications_count** | **float** | The number of applications for this Job posting. | 
**company_apply_url** | **str** | The application form URL of the company that published the Job posting. | [optional] 
**tracking_pixel_url** | **str** | The tracking pixel URL of the company that published the Job posting. | [optional] 
**screening_questions** | [**List[GetClassicJobPosting200ResponseScreeningQuestionsInner]**](GetClassicJobPosting200ResponseScreeningQuestionsInner.md) | The screening questions of the Job posting. | 
**salary** | **str** | The salary offered in the job posting. | [optional] 
**benefits** | **List[Optional[str]]** | A list of benefits offered in the Job posting. | [optional] 
**hiring_team** | [**List[GetClassicJobPosting200ResponseHiringTeamInner]**](GetClassicJobPosting200ResponseHiringTeamInner.md) | A list of hiring team members for the Job posting. | [optional] 

## Example

```python
from unipile.models.get_classic_job_posting200_response import GetClassicJobPosting200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicJobPosting200Response from a JSON string
get_classic_job_posting200_response_instance = GetClassicJobPosting200Response.from_json(json)
# print the JSON string representation of the object
print(GetClassicJobPosting200Response.to_json())

# convert the object into a dict
get_classic_job_posting200_response_dict = get_classic_job_posting200_response_instance.to_dict()
# create an instance of GetClassicJobPosting200Response from a dict
get_classic_job_posting200_response_from_dict = GetClassicJobPosting200Response.from_dict(get_classic_job_posting200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


