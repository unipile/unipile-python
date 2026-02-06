# GetClassicApplicants200ResponseDataInnerProfileEducationsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**school** | [**GetClassicApplicants200ResponseDataInnerProfileEducationsInnerSchool**](GetClassicApplicants200ResponseDataInnerProfileEducationsInnerSchool.md) |  | 
**degree** | **str** | The name of the degree. | [optional] 
**description** | **str** | The description of the education. | [optional] 
**field_of_study** | **str** | The field of study of the education. | [optional] 
**grade** | **str** | The reached academic level of the education. | [optional] 
**started_on** | **str** | The start date of the education in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | The end date of the education in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.get_classic_applicants200_response_data_inner_profile_educations_inner import GetClassicApplicants200ResponseDataInnerProfileEducationsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicants200ResponseDataInnerProfileEducationsInner from a JSON string
get_classic_applicants200_response_data_inner_profile_educations_inner_instance = GetClassicApplicants200ResponseDataInnerProfileEducationsInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicants200ResponseDataInnerProfileEducationsInner.to_json())

# convert the object into a dict
get_classic_applicants200_response_data_inner_profile_educations_inner_dict = get_classic_applicants200_response_data_inner_profile_educations_inner_instance.to_dict()
# create an instance of GetClassicApplicants200ResponseDataInnerProfileEducationsInner from a dict
get_classic_applicants200_response_data_inner_profile_educations_inner_from_dict = GetClassicApplicants200ResponseDataInnerProfileEducationsInner.from_dict(get_classic_applicants200_response_data_inner_profile_educations_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


