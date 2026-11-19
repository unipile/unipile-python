# PostPermissions

The permissions for the account owner on the post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**can_share** | **bool** | Whether the account owner can share the post. | 
**can_react** | **bool** | Whether the account owner can react to the post. | 
**can_post_comments** | **bool** | Whether the account owner can comment on the post. | 

## Example

```python
from unipile.models.post_permissions import PostPermissions

# TODO update the JSON string below
json = "{}"
# create an instance of PostPermissions from a JSON string
post_permissions_instance = PostPermissions.from_json(json)
# print the JSON string representation of the object
print(PostPermissions.to_json())

# convert the object into a dict
post_permissions_dict = post_permissions_instance.to_dict()
# create an instance of PostPermissions from a dict
post_permissions_from_dict = PostPermissions.from_dict(post_permissions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


