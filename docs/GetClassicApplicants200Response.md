# GetClassicApplicants200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetClassicApplicants200ResponseDataInner]**](GetClassicApplicants200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.get_classic_applicants200_response import GetClassicApplicants200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicants200Response from a JSON string
get_classic_applicants200_response_instance = GetClassicApplicants200Response.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicants200Response.to_json())

# convert the object into a dict
get_classic_applicants200_response_dict = get_classic_applicants200_response_instance.to_dict()
# create an instance of GetClassicApplicants200Response from a dict
get_classic_applicants200_response_from_dict = GetClassicApplicants200Response.from_dict(get_classic_applicants200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


