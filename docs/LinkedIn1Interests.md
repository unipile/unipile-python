# LinkedIn1Interests

The user's interests.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**top_voices** | [**List[LinkedIn1InterestsTopVoicesInner]**](LinkedIn1InterestsTopVoicesInner.md) | A collection of Top voice User profiles. | [optional] 
**companies** | [**List[LinkedIn1InterestsCompaniesInner]**](LinkedIn1InterestsCompaniesInner.md) | A collection of Companies. | [optional] 
**schools** | [**List[LinkedIn1InterestsSchoolsInner]**](LinkedIn1InterestsSchoolsInner.md) | A collection of Schools. | [optional] 
**newsletters** | [**List[LinkedIn1InterestsNewslettersInner]**](LinkedIn1InterestsNewslettersInner.md) | A collection of Newsletters. | [optional] 
**groups** | [**List[LinkedIn1InterestsGroupsInner]**](LinkedIn1InterestsGroupsInner.md) | A collection of Groups. | [optional] 

## Example

```python
from unipile.models.linked_in1_interests import LinkedIn1Interests

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1Interests from a JSON string
linked_in1_interests_instance = LinkedIn1Interests.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1Interests.to_json())

# convert the object into a dict
linked_in1_interests_dict = linked_in1_interests_instance.to_dict()
# create an instance of LinkedIn1Interests from a dict
linked_in1_interests_from_dict = LinkedIn1Interests.from_dict(linked_in1_interests_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


