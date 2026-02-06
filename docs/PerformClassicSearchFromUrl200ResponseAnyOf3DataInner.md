# PerformClassicSearchFromUrl200ResponseAnyOf3DataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The ID of the Company. | 
**display_name** | **str** | The display name of the Company. | 
**public_identifier** | **str** | The public identifier of the Company. | [optional] 
**profile_url** | **str** | The profile URL of the Company. | [optional] 
**public_picture_url** | **str** | The public picture URL of the Company. | [optional] 
**location** | **str** | The location of the Company. | [optional] 
**industry** | **str** | The industry to which the Company belongs. | [optional] 
**summary** | **str** | The summary of the Company&#39;s activities. | [optional] 
**headcount** | **str** | The number of employees of the Company. | [optional] 
**job_postings_count** | **float** | The number of job postings published by the Company. | [optional] 
**followers_count** | **float** | The number of the followers of the Company. | [optional] 
**relations_count** | **float** | The number of the relations of the Company. | [optional] 

## Example

```python
from unipile.models.perform_classic_search_from_url200_response_any_of3_data_inner import PerformClassicSearchFromUrl200ResponseAnyOf3DataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf3DataInner from a JSON string
perform_classic_search_from_url200_response_any_of3_data_inner_instance = PerformClassicSearchFromUrl200ResponseAnyOf3DataInner.from_json(json)
# print the JSON string representation of the object
print(PerformClassicSearchFromUrl200ResponseAnyOf3DataInner.to_json())

# convert the object into a dict
perform_classic_search_from_url200_response_any_of3_data_inner_dict = perform_classic_search_from_url200_response_any_of3_data_inner_instance.to_dict()
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf3DataInner from a dict
perform_classic_search_from_url200_response_any_of3_data_inner_from_dict = PerformClassicSearchFromUrl200ResponseAnyOf3DataInner.from_dict(perform_classic_search_from_url200_response_any_of3_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


