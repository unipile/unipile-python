# GetRecruiterHiringProjectList200ResponseDataInnerOwner

The owner of the Project.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Project owner. | 
**seat_id** | **str** | The seat ID of the Project owner. | 
**name** | **str** | The name of the Project owner. | 
**email** | **str** | The email address of the Project owner. | 
**profile_url** | **str** | The profile URL of the Project owner. | 
**profile_headline** | **str** | The profile headline of the Project owner. | 
**public_picture_url** | **str** | The profile picture URL of the Project owner. | [optional] 

## Example

```python
from unipile.models.get_recruiter_hiring_project_list200_response_data_inner_owner import GetRecruiterHiringProjectList200ResponseDataInnerOwner

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerOwner from a JSON string
get_recruiter_hiring_project_list200_response_data_inner_owner_instance = GetRecruiterHiringProjectList200ResponseDataInnerOwner.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProjectList200ResponseDataInnerOwner.to_json())

# convert the object into a dict
get_recruiter_hiring_project_list200_response_data_inner_owner_dict = get_recruiter_hiring_project_list200_response_data_inner_owner_instance.to_dict()
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerOwner from a dict
get_recruiter_hiring_project_list200_response_data_inner_owner_from_dict = GetRecruiterHiringProjectList200ResponseDataInnerOwner.from_dict(get_recruiter_hiring_project_list200_response_data_inner_owner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


