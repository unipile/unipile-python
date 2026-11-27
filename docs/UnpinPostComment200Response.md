# UnpinPostComment200Response

Result of unpinning a comment from a post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | Confirms that the comment is no longer pinned on the post. | 

## Example

```python
from unipile.models.unpin_post_comment200_response import UnpinPostComment200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UnpinPostComment200Response from a JSON string
unpin_post_comment200_response_instance = UnpinPostComment200Response.from_json(json)
# print the JSON string representation of the object
print(UnpinPostComment200Response.to_json())

# convert the object into a dict
unpin_post_comment200_response_dict = unpin_post_comment200_response_instance.to_dict()
# create an instance of UnpinPostComment200Response from a dict
unpin_post_comment200_response_from_dict = UnpinPostComment200Response.from_dict(unpin_post_comment200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


