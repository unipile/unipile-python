# GetPostsList200ResponseDataInnerPoll

Data about the poll if the post is a poll.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the poll. | 
**total_votes_count** | **float** | The total number of votes for the poll. | 
**question** | **str** | The question of the poll. | 
**is_open** | **bool** | Whether the poll is open. If the poll is closed, the user can only see the results. | 
**options** | [**List[GetPostsList200ResponseDataInnerPollOptionsInner]**](GetPostsList200ResponseDataInnerPollOptionsInner.md) |  | 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_poll import GetPostsList200ResponseDataInnerPoll

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerPoll from a JSON string
get_posts_list200_response_data_inner_poll_instance = GetPostsList200ResponseDataInnerPoll.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerPoll.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_poll_dict = get_posts_list200_response_data_inner_poll_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerPoll from a dict
get_posts_list200_response_data_inner_poll_from_dict = GetPostsList200ResponseDataInnerPoll.from_dict(get_posts_list200_response_data_inner_poll_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


