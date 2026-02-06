# PerformClassicSearchFromUrl200ResponseAnyOfDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the Job posting. | 
**title** | **str** | The title of the Job posting. | 
**location** | **str** | The location of the Job posting. | [optional] 
**listed_at** | **str** | The creation date of the Job posting. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**workplace_type** | **str** | The type of workplace of the Job posting. | [optional] 
**url** | **str** | The URL of the Job posting. | 
**is_repost** | **bool** | Whether the Job posting is a repost. | 
**is_promoted** | **bool** | Whether the Job posting has been promoted. | 
**easy_apply** | **bool** | Whether applicants are allowed to apply to the Job posting directly on LinkedIn. | 
**few_applicants** | **bool** | Whether the Job posting received a limited number of applications. | 
**company** | [**PerformClassicSearchFromUrl200ResponseAnyOfDataInnerCompany**](PerformClassicSearchFromUrl200ResponseAnyOfDataInnerCompany.md) |  | 
**insights** | **List[Optional[str]]** | A list of insights about the Job posting. | 

## Example

```python
from unipile.models.perform_classic_search_from_url200_response_any_of_data_inner import PerformClassicSearchFromUrl200ResponseAnyOfDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOfDataInner from a JSON string
perform_classic_search_from_url200_response_any_of_data_inner_instance = PerformClassicSearchFromUrl200ResponseAnyOfDataInner.from_json(json)
# print the JSON string representation of the object
print(PerformClassicSearchFromUrl200ResponseAnyOfDataInner.to_json())

# convert the object into a dict
perform_classic_search_from_url200_response_any_of_data_inner_dict = perform_classic_search_from_url200_response_any_of_data_inner_instance.to_dict()
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOfDataInner from a dict
perform_classic_search_from_url200_response_any_of_data_inner_from_dict = PerformClassicSearchFromUrl200ResponseAnyOfDataInner.from_dict(perform_classic_search_from_url200_response_any_of_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


