# GetPostsList200ResponseDataInnerSpecificsJobPostingCompany

The company that published the job posting.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the company. | 
**name** | **str** | Name of the company. | 
**picture_url** | **str** | Public url to the profile picture of the company. | [optional] 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_specifics_job_posting_company import GetPostsList200ResponseDataInnerSpecificsJobPostingCompany

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerSpecificsJobPostingCompany from a JSON string
get_posts_list200_response_data_inner_specifics_job_posting_company_instance = GetPostsList200ResponseDataInnerSpecificsJobPostingCompany.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerSpecificsJobPostingCompany.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_specifics_job_posting_company_dict = get_posts_list200_response_data_inner_specifics_job_posting_company_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerSpecificsJobPostingCompany from a dict
get_posts_list200_response_data_inner_specifics_job_posting_company_from_dict = GetPostsList200ResponseDataInnerSpecificsJobPostingCompany.from_dict(get_posts_list200_response_data_inner_specifics_job_posting_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


