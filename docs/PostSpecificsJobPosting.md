# PostSpecificsJobPosting

A job posting that can be included as an insert in the post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the job posting. | 
**title** | **str** | Title of the job posting. | 
**location** | **str** | Location of the job posting. | 
**company** | [**PostSpecificsJobPostingCompany**](PostSpecificsJobPostingCompany.md) |  | 

## Example

```python
from unipile.models.post_specifics_job_posting import PostSpecificsJobPosting

# TODO update the JSON string below
json = "{}"
# create an instance of PostSpecificsJobPosting from a JSON string
post_specifics_job_posting_instance = PostSpecificsJobPosting.from_json(json)
# print the JSON string representation of the object
print(PostSpecificsJobPosting.to_json())

# convert the object into a dict
post_specifics_job_posting_dict = post_specifics_job_posting_instance.to_dict()
# create an instance of PostSpecificsJobPosting from a dict
post_specifics_job_posting_from_dict = PostSpecificsJobPosting.from_dict(post_specifics_job_posting_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


