# DeleteAnExperience


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**operation** | **str** |  | 
**id** | **str** | ID of the experience to delete. | 

## Example

```python
from unipile.models.delete_an_experience import DeleteAnExperience

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteAnExperience from a JSON string
delete_an_experience_instance = DeleteAnExperience.from_json(json)
# print the JSON string representation of the object
print(DeleteAnExperience.to_json())

# convert the object into a dict
delete_an_experience_dict = delete_an_experience_instance.to_dict()
# create an instance of DeleteAnExperience from a dict
delete_an_experience_from_dict = DeleteAnExperience.from_dict(delete_an_experience_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


