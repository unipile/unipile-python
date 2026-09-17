# ListScopes200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the returned collection. | 
**data** | [**List[ListScopes200ResponseDataInner]**](ListScopes200ResponseDataInner.md) | The scopes in the current page. | 
**has_more** | **bool** | Whether more scopes are available after the current page. | 

## Example

```python
from unipile.models.list_scopes200_response import ListScopes200Response

# TODO update the JSON string below
json = "{}"
# create an instance of ListScopes200Response from a JSON string
list_scopes200_response_instance = ListScopes200Response.from_json(json)
# print the JSON string representation of the object
print(ListScopes200Response.to_json())

# convert the object into a dict
list_scopes200_response_dict = list_scopes200_response_instance.to_dict()
# create an instance of ListScopes200Response from a dict
list_scopes200_response_from_dict = ListScopes200Response.from_dict(list_scopes200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


