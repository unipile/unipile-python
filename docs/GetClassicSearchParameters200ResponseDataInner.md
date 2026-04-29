# GetClassicSearchParameters200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The identifier of the search parameter. | 
**name** | **str** | The display name of the search parameter. | 
**metadata** | [**GetClassicSearchParameters200ResponseDataInnerMetadata**](GetClassicSearchParameters200ResponseDataInnerMetadata.md) |  | [optional] 

## Example

```python
from unipile.models.get_classic_search_parameters200_response_data_inner import GetClassicSearchParameters200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicSearchParameters200ResponseDataInner from a JSON string
get_classic_search_parameters200_response_data_inner_instance = GetClassicSearchParameters200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicSearchParameters200ResponseDataInner.to_json())

# convert the object into a dict
get_classic_search_parameters200_response_data_inner_dict = get_classic_search_parameters200_response_data_inner_instance.to_dict()
# create an instance of GetClassicSearchParameters200ResponseDataInner from a dict
get_classic_search_parameters200_response_data_inner_from_dict = GetClassicSearchParameters200ResponseDataInner.from_dict(get_classic_search_parameters200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


