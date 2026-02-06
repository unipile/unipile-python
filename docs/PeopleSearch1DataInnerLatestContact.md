# PeopleSearch1DataInnerLatestContact

The last contact you had with the User.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**performed_at** | **str** | The date on which the action was performed. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**resource_id** | **str** | The ID of the resource that may have been created, like a message or an invitation. | [optional] 

## Example

```python
from unipile.models.people_search1_data_inner_latest_contact import PeopleSearch1DataInnerLatestContact

# TODO update the JSON string below
json = "{}"
# create an instance of PeopleSearch1DataInnerLatestContact from a JSON string
people_search1_data_inner_latest_contact_instance = PeopleSearch1DataInnerLatestContact.from_json(json)
# print the JSON string representation of the object
print(PeopleSearch1DataInnerLatestContact.to_json())

# convert the object into a dict
people_search1_data_inner_latest_contact_dict = people_search1_data_inner_latest_contact_instance.to_dict()
# create an instance of PeopleSearch1DataInnerLatestContact from a dict
people_search1_data_inner_latest_contact_from_dict = PeopleSearch1DataInnerLatestContact.from_dict(people_search1_data_inner_latest_contact_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


