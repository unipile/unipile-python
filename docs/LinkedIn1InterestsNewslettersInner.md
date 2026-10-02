# LinkedIn1InterestsNewslettersInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the newsletter. | [optional] 
**title** | **str** | The title of the newsletter. | 
**url** | **str** | The URL to the newsletter. | [optional] 
**description** | **str** | The description of the newsletter. | [optional] 
**is_subscribed** | **bool** | Whether the current user has subscribed to the newsletter. | 
**posting_frequency** | **str** | The posting frequency of the newsletter. | [optional] 
**public_picture_url** | **str** | The public picture URL of the newsletter. | [optional] 

## Example

```python
from unipile.models.linked_in1_interests_newsletters_inner import LinkedIn1InterestsNewslettersInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1InterestsNewslettersInner from a JSON string
linked_in1_interests_newsletters_inner_instance = LinkedIn1InterestsNewslettersInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1InterestsNewslettersInner.to_json())

# convert the object into a dict
linked_in1_interests_newsletters_inner_dict = linked_in1_interests_newsletters_inner_instance.to_dict()
# create an instance of LinkedIn1InterestsNewslettersInner from a dict
linked_in1_interests_newsletters_inner_from_dict = LinkedIn1InterestsNewslettersInner.from_dict(linked_in1_interests_newsletters_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


