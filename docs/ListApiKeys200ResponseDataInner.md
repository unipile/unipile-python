# ListApiKeys200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the returned object. | 
**id** | **str** | The unique public ID of the API Key. | 
**application_id** | **str** | The ID of the Application that owns the API Key. | 
**prefix** | **str** | The non-secret prefix used to identify the API Key. | 
**issued_at** | **str** | The date and time when the API Key was created. | 
**expires_at** | **str** | The date and time when the API Key expires. | 
**name** | **str** | The internal name of the API Key. | 
**role** | **str** | The effective access role: &#x60;service&#x60; manages the Application, &#x60;account&#x60; accesses every Account, and &#x60;scoped&#x60; accesses one Scope. | 
**account_scope_id** | **str** | The Scope accessible to the API Key, or &#x60;null&#x60; for service and global Account API Keys. | 

## Example

```python
from unipile.models.list_api_keys200_response_data_inner import ListApiKeys200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of ListApiKeys200ResponseDataInner from a JSON string
list_api_keys200_response_data_inner_instance = ListApiKeys200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(ListApiKeys200ResponseDataInner.to_json())

# convert the object into a dict
list_api_keys200_response_data_inner_dict = list_api_keys200_response_data_inner_instance.to_dict()
# create an instance of ListApiKeys200ResponseDataInner from a dict
list_api_keys200_response_data_inner_from_dict = ListApiKeys200ResponseDataInner.from_dict(list_api_keys200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


