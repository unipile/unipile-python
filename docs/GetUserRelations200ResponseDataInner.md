# GetUserRelations200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the user relation for the provider. Usually an internal identifier used by the API only. | 
**object** | **str** |  | 
**user** | [**GetUserRelations200ResponseDataInnerUser**](GetUserRelations200ResponseDataInnerUser.md) |  | 
**created_at** | **str** | Date and time when the relation was created.  | [optional] 

## Example

```python
from unipile.models.get_user_relations200_response_data_inner import GetUserRelations200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserRelations200ResponseDataInner from a JSON string
get_user_relations200_response_data_inner_instance = GetUserRelations200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetUserRelations200ResponseDataInner.to_json())

# convert the object into a dict
get_user_relations200_response_data_inner_dict = get_user_relations200_response_data_inner_instance.to_dict()
# create an instance of GetUserRelations200ResponseDataInner from a dict
get_user_relations200_response_data_inner_from_dict = GetUserRelations200ResponseDataInner.from_dict(get_user_relations200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


