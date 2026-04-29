# SearchOrJobPostingSourced


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | 
**keywords** | **str** | A keyword or group of keywords to filter results. Not applicable to JOB_FUNCTION, PROFILE_LANGUAGE and CUSTOM_FILTER. | [optional] 
**type** | **str** | The type of search parameter. | 
**offset** | **float** | An offset used for pagination. Not applicable to JOB_FUNCTION. | [optional] 
**limit** | **float** | Not applicable to JOB_FUNCTION. | [optional] [default to 10]

## Example

```python
from unipile.models.search_or_job_posting_sourced import SearchOrJobPostingSourced

# TODO update the JSON string below
json = "{}"
# create an instance of SearchOrJobPostingSourced from a JSON string
search_or_job_posting_sourced_instance = SearchOrJobPostingSourced.from_json(json)
# print the JSON string representation of the object
print(SearchOrJobPostingSourced.to_json())

# convert the object into a dict
search_or_job_posting_sourced_dict = search_or_job_posting_sourced_instance.to_dict()
# create an instance of SearchOrJobPostingSourced from a dict
search_or_job_posting_sourced_from_dict = SearchOrJobPostingSourced.from_dict(search_or_job_posting_sourced_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


