# GetPostsList200ResponseDataInnerPollOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the option. | 
**text** | **str** | The displayed text of the option. | 
**win** | **bool** | Whether the option is the winning option. | 
**votes_count** | **float** | The number of votes for this option. | 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_poll_options_inner import GetPostsList200ResponseDataInnerPollOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerPollOptionsInner from a JSON string
get_posts_list200_response_data_inner_poll_options_inner_instance = GetPostsList200ResponseDataInnerPollOptionsInner.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerPollOptionsInner.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_poll_options_inner_dict = get_posts_list200_response_data_inner_poll_options_inner_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerPollOptionsInner from a dict
get_posts_list200_response_data_inner_poll_options_inner_from_dict = GetPostsList200ResponseDataInnerPollOptionsInner.from_dict(get_posts_list200_response_data_inner_poll_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


