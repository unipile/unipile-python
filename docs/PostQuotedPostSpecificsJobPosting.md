# PostQuotedPostSpecificsJobPosting

A job posting that can be included as an insert in the post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The text content of the message, when available. | 
**title** | **str** | Title of the job posting. | 
**location** | **str** | Location of the job posting. | 
**company** | [**PostQuotedPostSpecificsJobPostingCompany**](PostQuotedPostSpecificsJobPostingCompany.md) |  | 

## Example

```python
from unipile.models.post_quoted_post_specifics_job_posting import PostQuotedPostSpecificsJobPosting

# TODO update the JSON string below
json = "{}"
# create an instance of PostQuotedPostSpecificsJobPosting from a JSON string
post_quoted_post_specifics_job_posting_instance = PostQuotedPostSpecificsJobPosting.from_json(json)
# print the JSON string representation of the object
print(PostQuotedPostSpecificsJobPosting.to_json())

# convert the object into a dict
post_quoted_post_specifics_job_posting_dict = post_quoted_post_specifics_job_posting_instance.to_dict()
# create an instance of PostQuotedPostSpecificsJobPosting from a dict
post_quoted_post_specifics_job_posting_from_dict = PostQuotedPostSpecificsJobPosting.from_dict(post_quoted_post_specifics_job_posting_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


