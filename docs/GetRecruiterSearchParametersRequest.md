# GetRecruiterSearchParametersRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | 
**project_id** | **str** | The ID of the Project the Pipeline belongs to. | 
**channel_id** | **str** | In Talent Pool context, the ID of the JOB_POSTING Channel to get parameters from. | 
**keywords** | **str** | A keyword or group of keywords to filter results. | [optional] 
**type** | **str** | The type of search parameter. | 
**stage_id** | **str** | In Pipeline context, the ID of the Stage to get parameters from. Leave undefined to get results from all stages. | [optional] 
**offset** | **float** | An offset used for pagination. | [optional] 
**limit** | **float** | The limit of items to be returned. | [optional] [default to 10]

## Example

```python
from unipile.models.get_recruiter_search_parameters_request import GetRecruiterSearchParametersRequest

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterSearchParametersRequest from a JSON string
get_recruiter_search_parameters_request_instance = GetRecruiterSearchParametersRequest.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterSearchParametersRequest.to_json())

# convert the object into a dict
get_recruiter_search_parameters_request_dict = get_recruiter_search_parameters_request_instance.to_dict()
# create an instance of GetRecruiterSearchParametersRequest from a dict
get_recruiter_search_parameters_request_from_dict = GetRecruiterSearchParametersRequest.from_dict(get_recruiter_search_parameters_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


