# ListClassicUserJobPostings200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The ID of the Job posting. | 
**title** | **str** | The title of the Job posting. | 
**company** | **str** | The company that published the Job posting. | 
**location** | **str** | The location of the Job posting. | 
**state** | **str** | The state of the Job posting. | 
**applications_count** | **float** | The number of applications for this job posting. | 

## Example

```python
from unipile.models.list_classic_user_job_postings200_response_data_inner import ListClassicUserJobPostings200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of ListClassicUserJobPostings200ResponseDataInner from a JSON string
list_classic_user_job_postings200_response_data_inner_instance = ListClassicUserJobPostings200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(ListClassicUserJobPostings200ResponseDataInner.to_json())

# convert the object into a dict
list_classic_user_job_postings200_response_data_inner_dict = list_classic_user_job_postings200_response_data_inner_instance.to_dict()
# create an instance of ListClassicUserJobPostings200ResponseDataInner from a dict
list_classic_user_job_postings200_response_data_inner_from_dict = ListClassicUserJobPostings200ResponseDataInner.from_dict(list_classic_user_job_postings200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


