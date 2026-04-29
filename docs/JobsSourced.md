# JobsSourced


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | 
**keywords** | **str** | A keyword or group of keywords to filter results. | [optional] 
**type** | **str** | The type of search parameter. | 
**offset** | **float** | An offset used for pagination. | [optional] 
**limit** | **float** | The limit of items to be returned. | [optional] [default to 10]

## Example

```python
from unipile.models.jobs_sourced import JobsSourced

# TODO update the JSON string below
json = "{}"
# create an instance of JobsSourced from a JSON string
jobs_sourced_instance = JobsSourced.from_json(json)
# print the JSON string representation of the object
print(JobsSourced.to_json())

# convert the object into a dict
jobs_sourced_dict = jobs_sourced_instance.to_dict()
# create an instance of JobsSourced from a dict
jobs_sourced_from_dict = JobsSourced.from_dict(jobs_sourced_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


