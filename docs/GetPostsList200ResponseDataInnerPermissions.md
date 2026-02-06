# GetPostsList200ResponseDataInnerPermissions

The permissions for the account owner on the post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**can_share** | **bool** | Whether the account owner can share the post. | 
**can_react** | **bool** | Whether the account owner can react to the post. | 
**can_post_comments** | **bool** | Whether the account owner can comment on the post. | 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_permissions import GetPostsList200ResponseDataInnerPermissions

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerPermissions from a JSON string
get_posts_list200_response_data_inner_permissions_instance = GetPostsList200ResponseDataInnerPermissions.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerPermissions.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_permissions_dict = get_posts_list200_response_data_inner_permissions_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerPermissions from a dict
get_posts_list200_response_data_inner_permissions_from_dict = GetPostsList200ResponseDataInnerPermissions.from_dict(get_posts_list200_response_data_inner_permissions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


