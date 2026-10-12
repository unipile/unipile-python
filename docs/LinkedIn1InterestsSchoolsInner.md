# LinkedIn1InterestsSchoolsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Company for the provider. | 
**name** | **str** | The name of the Company. | 
**profile_url** | **str** | The public profile URL of the Company. | [optional] 
**public_picture_url** | **str** | The public picture URL of the Company. | [optional] 
**public_identifier** | **str** | The public identifier of the Company. | [optional] 
**followers_count** | **float** | The number of followers of the Company. | [optional] 
**is_following** | **bool** | Whether the current user is following the Company. | [optional] 
**object** | **str** |  | 

## Example

```python
from unipile.models.linked_in1_interests_schools_inner import LinkedIn1InterestsSchoolsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1InterestsSchoolsInner from a JSON string
linked_in1_interests_schools_inner_instance = LinkedIn1InterestsSchoolsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1InterestsSchoolsInner.to_json())

# convert the object into a dict
linked_in1_interests_schools_inner_dict = linked_in1_interests_schools_inner_instance.to_dict()
# create an instance of LinkedIn1InterestsSchoolsInner from a dict
linked_in1_interests_schools_inner_from_dict = LinkedIn1InterestsSchoolsInner.from_dict(linked_in1_interests_schools_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


