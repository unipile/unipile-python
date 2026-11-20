# PostQuotedPostSpecificsJobPostingCompany

The company that published the job posting.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The text content of the message, when available. | 
**name** | **str** | The text content of the message, when available. | 
**picture_url** | **str** | Public url to the profile picture of the company. | [optional] 

## Example

```python
from unipile.models.post_quoted_post_specifics_job_posting_company import PostQuotedPostSpecificsJobPostingCompany

# TODO update the JSON string below
json = "{}"
# create an instance of PostQuotedPostSpecificsJobPostingCompany from a JSON string
post_quoted_post_specifics_job_posting_company_instance = PostQuotedPostSpecificsJobPostingCompany.from_json(json)
# print the JSON string representation of the object
print(PostQuotedPostSpecificsJobPostingCompany.to_json())

# convert the object into a dict
post_quoted_post_specifics_job_posting_company_dict = post_quoted_post_specifics_job_posting_company_instance.to_dict()
# create an instance of PostQuotedPostSpecificsJobPostingCompany from a dict
post_quoted_post_specifics_job_posting_company_from_dict = PostQuotedPostSpecificsJobPostingCompany.from_dict(post_quoted_post_specifics_job_posting_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


