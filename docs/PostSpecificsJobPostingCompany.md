# PostSpecificsJobPostingCompany

The company that published the job posting.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the company. | 
**name** | **str** | Name of the company. | 
**picture_url** | **str** | Public url to the profile picture of the company. | [optional] 

## Example

```python
from unipile.models.post_specifics_job_posting_company import PostSpecificsJobPostingCompany

# TODO update the JSON string below
json = "{}"
# create an instance of PostSpecificsJobPostingCompany from a JSON string
post_specifics_job_posting_company_instance = PostSpecificsJobPostingCompany.from_json(json)
# print the JSON string representation of the object
print(PostSpecificsJobPostingCompany.to_json())

# convert the object into a dict
post_specifics_job_posting_company_dict = post_specifics_job_posting_company_instance.to_dict()
# create an instance of PostSpecificsJobPostingCompany from a dict
post_specifics_job_posting_company_from_dict = PostSpecificsJobPostingCompany.from_dict(post_specifics_job_posting_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


