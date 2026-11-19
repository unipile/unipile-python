# PostPollOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the option. | 
**text** | **str** | The displayed text of the option. | 
**win** | **bool** | Whether the option is the winning option. | 
**votes_count** | **float** | The number of votes for this option. | 

## Example

```python
from unipile.models.post_poll_options_inner import PostPollOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of PostPollOptionsInner from a JSON string
post_poll_options_inner_instance = PostPollOptionsInner.from_json(json)
# print the JSON string representation of the object
print(PostPollOptionsInner.to_json())

# convert the object into a dict
post_poll_options_inner_dict = post_poll_options_inner_instance.to_dict()
# create an instance of PostPollOptionsInner from a dict
post_poll_options_inner_from_dict = PostPollOptionsInner.from_dict(post_poll_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


