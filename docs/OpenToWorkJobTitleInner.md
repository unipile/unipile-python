# OpenToWorkJobTitleInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | The title of the job. | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getclassicsearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values. | 

## Example

```python
from unipile.models.open_to_work_job_title_inner import OpenToWorkJobTitleInner

# TODO update the JSON string below
json = "{}"
# create an instance of OpenToWorkJobTitleInner from a JSON string
open_to_work_job_title_inner_instance = OpenToWorkJobTitleInner.from_json(json)
# print the JSON string representation of the object
print(OpenToWorkJobTitleInner.to_json())

# convert the object into a dict
open_to_work_job_title_inner_dict = open_to_work_job_title_inner_instance.to_dict()
# create an instance of OpenToWorkJobTitleInner from a dict
open_to_work_job_title_inner_from_dict = OpenToWorkJobTitleInner.from_dict(open_to_work_job_title_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


