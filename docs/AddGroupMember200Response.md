# AddGroupMember200Response

The request to add or invite the member was successful.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object. | 

## Example

```python
from unipile.models.add_group_member200_response import AddGroupMember200Response

# TODO update the JSON string below
json = "{}"
# create an instance of AddGroupMember200Response from a JSON string
add_group_member200_response_instance = AddGroupMember200Response.from_json(json)
# print the JSON string representation of the object
print(AddGroupMember200Response.to_json())

# convert the object into a dict
add_group_member200_response_dict = add_group_member200_response_instance.to_dict()
# create an instance of AddGroupMember200Response from a dict
add_group_member200_response_from_dict = AddGroupMember200Response.from_dict(add_group_member200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


