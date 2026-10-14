# Resume

An activity related to a resume document in LinkedIn Recruiter.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_updated_at** | **str** | The time at which the activity was updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_updated_by** | [**LinkedIn1InterestsTopVoicesInner**](LinkedIn1InterestsTopVoicesInner.md) |  | 
**event** | **str** | Whether the resume was added, edited, or deleted. | 
**resume_id** | **str** | The LinkedIn ID of the resume document. | 
**filename** | **str** | The name of the resume file, including the extension. | 

## Example

```python
from unipile.models.resume import Resume

# TODO update the JSON string below
json = "{}"
# create an instance of Resume from a JSON string
resume_instance = Resume.from_json(json)
# print the JSON string representation of the object
print(Resume.to_json())

# convert the object into a dict
resume_dict = resume_instance.to_dict()
# create an instance of Resume from a dict
resume_from_dict = Resume.from_dict(resume_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


