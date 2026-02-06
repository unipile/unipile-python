# PeopleSearch1DataInnerContactInfo

Contact information of the User.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phones** | **List[Optional[str]]** | A list of phone numbers of the User. | [optional] 
**emails** | **List[Optional[str]]** | A list of email addresses of the User. | [optional] 

## Example

```python
from unipile.models.people_search1_data_inner_contact_info import PeopleSearch1DataInnerContactInfo

# TODO update the JSON string below
json = "{}"
# create an instance of PeopleSearch1DataInnerContactInfo from a JSON string
people_search1_data_inner_contact_info_instance = PeopleSearch1DataInnerContactInfo.from_json(json)
# print the JSON string representation of the object
print(PeopleSearch1DataInnerContactInfo.to_json())

# convert the object into a dict
people_search1_data_inner_contact_info_dict = people_search1_data_inner_contact_info_instance.to_dict()
# create an instance of PeopleSearch1DataInnerContactInfo from a dict
people_search1_data_inner_contact_info_from_dict = PeopleSearch1DataInnerContactInfo.from_dict(people_search1_data_inner_contact_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


