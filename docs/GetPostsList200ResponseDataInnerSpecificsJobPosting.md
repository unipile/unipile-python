# GetPostsList200ResponseDataInnerSpecificsJobPosting

A job posting that can be included as an insert in the post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the job posting. | 
**title** | **str** | Title of the job posting. | 
**location** | **str** | Location of the job posting. | 
**company** | [**GetPostsList200ResponseDataInnerSpecificsJobPostingCompany**](GetPostsList200ResponseDataInnerSpecificsJobPostingCompany.md) |  | 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_specifics_job_posting import GetPostsList200ResponseDataInnerSpecificsJobPosting

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerSpecificsJobPosting from a JSON string
get_posts_list200_response_data_inner_specifics_job_posting_instance = GetPostsList200ResponseDataInnerSpecificsJobPosting.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerSpecificsJobPosting.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_specifics_job_posting_dict = get_posts_list200_response_data_inner_specifics_job_posting_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerSpecificsJobPosting from a dict
get_posts_list200_response_data_inner_specifics_job_posting_from_dict = GetPostsList200ResponseDataInnerSpecificsJobPosting.from_dict(get_posts_list200_response_data_inner_specifics_job_posting_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


