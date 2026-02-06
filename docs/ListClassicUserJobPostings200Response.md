# ListClassicUserJobPostings200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[ListClassicUserJobPostings200ResponseDataInner]**](ListClassicUserJobPostings200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.list_classic_user_job_postings200_response import ListClassicUserJobPostings200Response

# TODO update the JSON string below
json = "{}"
# create an instance of ListClassicUserJobPostings200Response from a JSON string
list_classic_user_job_postings200_response_instance = ListClassicUserJobPostings200Response.from_json(json)
# print the JSON string representation of the object
print(ListClassicUserJobPostings200Response.to_json())

# convert the object into a dict
list_classic_user_job_postings200_response_dict = list_classic_user_job_postings200_response_instance.to_dict()
# create an instance of ListClassicUserJobPostings200Response from a dict
list_classic_user_job_postings200_response_from_dict = ListClassicUserJobPostings200Response.from_dict(list_classic_user_job_postings200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


