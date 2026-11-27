# PostPoll

Data about the poll if the post is a poll.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the poll. | 
**total_votes_count** | **float** | The total number of votes for the poll. | 
**question** | **str** | The question of the poll. | 
**is_open** | **bool** | Whether the poll is open. If the poll is closed, the user can only see the results. | 
**options** | [**List[PostPollOptionsInner]**](PostPollOptionsInner.md) |  | 

## Example

```python
from unipile.models.post_poll import PostPoll

# TODO update the JSON string below
json = "{}"
# create an instance of PostPoll from a JSON string
post_poll_instance = PostPoll.from_json(json)
# print the JSON string representation of the object
print(PostPoll.to_json())

# convert the object into a dict
post_poll_dict = post_poll_instance.to_dict()
# create an instance of PostPoll from a dict
post_poll_from_dict = PostPoll.from_dict(post_poll_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


