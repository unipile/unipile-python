# PerformClassicJobsSearchRequestSalary

The minimum salary.    Native filter : Salary   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** |  | 
**starting_from** | **float** | The minimum amount. | 

## Example

```python
from unipile.models.perform_classic_jobs_search_request_salary import PerformClassicJobsSearchRequestSalary

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicJobsSearchRequestSalary from a JSON string
perform_classic_jobs_search_request_salary_instance = PerformClassicJobsSearchRequestSalary.from_json(json)
# print the JSON string representation of the object
print(PerformClassicJobsSearchRequestSalary.to_json())

# convert the object into a dict
perform_classic_jobs_search_request_salary_dict = perform_classic_jobs_search_request_salary_instance.to_dict()
# create an instance of PerformClassicJobsSearchRequestSalary from a dict
perform_classic_jobs_search_request_salary_from_dict = PerformClassicJobsSearchRequestSalary.from_dict(perform_classic_jobs_search_request_salary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


