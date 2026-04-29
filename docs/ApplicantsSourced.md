# ApplicantsSourced


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | 
**project_id** | **str** | The ID of the Project associated with the Talent pool. | 
**channel_id** | **str** | In Talent Pool context, the ID of the JOB_POSTING Channel to get parameters from. | 
**keywords** | **str** | A keyword or group of keywords to filter results. Applicable to TAG only. | [optional] 
**type** | **str** | The type of search parameter. | 

## Example

```python
from unipile.models.applicants_sourced import ApplicantsSourced

# TODO update the JSON string below
json = "{}"
# create an instance of ApplicantsSourced from a JSON string
applicants_sourced_instance = ApplicantsSourced.from_json(json)
# print the JSON string representation of the object
print(ApplicantsSourced.to_json())

# convert the object into a dict
applicants_sourced_dict = applicants_sourced_instance.to_dict()
# create an instance of ApplicantsSourced from a dict
applicants_sourced_from_dict = ApplicantsSourced.from_dict(applicants_sourced_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


