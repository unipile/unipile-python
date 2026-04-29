# GetClassicSearchParameters200ResponseDataInnerMetadata

Metadata about the current parameter.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**last_viewed_at** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**new_results_count** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**query** | **str** | The ID of the Company. | 
**project** | [**RecruiterSavedSearchProject**](RecruiterSavedSearchProject.md) |  | [optional] 

## Example

```python
from unipile.models.get_classic_search_parameters200_response_data_inner_metadata import GetClassicSearchParameters200ResponseDataInnerMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicSearchParameters200ResponseDataInnerMetadata from a JSON string
get_classic_search_parameters200_response_data_inner_metadata_instance = GetClassicSearchParameters200ResponseDataInnerMetadata.from_json(json)
# print the JSON string representation of the object
print(GetClassicSearchParameters200ResponseDataInnerMetadata.to_json())

# convert the object into a dict
get_classic_search_parameters200_response_data_inner_metadata_dict = get_classic_search_parameters200_response_data_inner_metadata_instance.to_dict()
# create an instance of GetClassicSearchParameters200ResponseDataInnerMetadata from a dict
get_classic_search_parameters200_response_data_inner_metadata_from_dict = GetClassicSearchParameters200ResponseDataInnerMetadata.from_dict(get_classic_search_parameters200_response_data_inner_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


