# OpenToWork


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | [**List[OpenToWorkJobTitleInner]**](OpenToWorkJobTitleInner.md) | A list of job titles you would like to hold. | 
**workplace** | [**List[OpenToWorkWorkplaceInner]**](OpenToWorkWorkplaceInner.md) | A list of desired workplaces. | 
**start_date** | **str** | The timeframe by which you would like to start. | [optional] 
**employment_type** | **List[str]** | A list of employment types. | [optional] 
**visibility** | **str** | Who can view that you are open to work. | 

## Example

```python
from unipile.models.open_to_work import OpenToWork

# TODO update the JSON string below
json = "{}"
# create an instance of OpenToWork from a JSON string
open_to_work_instance = OpenToWork.from_json(json)
# print the JSON string representation of the object
print(OpenToWork.to_json())

# convert the object into a dict
open_to_work_dict = open_to_work_instance.to_dict()
# create an instance of OpenToWork from a dict
open_to_work_from_dict = OpenToWork.from_dict(open_to_work_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


