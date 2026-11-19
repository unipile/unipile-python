# PostUserReacted

If the account owner has reacted to this post, the value of the reaction (emoji unicode or reaction type), `true` if no details on the reaction, else `false`.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.post_user_reacted import PostUserReacted

# TODO update the JSON string below
json = "{}"
# create an instance of PostUserReacted from a JSON string
post_user_reacted_instance = PostUserReacted.from_json(json)
# print the JSON string representation of the object
print(PostUserReacted.to_json())

# convert the object into a dict
post_user_reacted_dict = post_user_reacted_instance.to_dict()
# create an instance of PostUserReacted from a dict
post_user_reacted_from_dict = PostUserReacted.from_dict(post_user_reacted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


