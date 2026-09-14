# DeleteAnEducation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**operation** | **str** |  | 
**id** | **str** | ID of the education to delete. | 

## Example

```python
from unipile.models.delete_an_education import DeleteAnEducation

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteAnEducation from a JSON string
delete_an_education_instance = DeleteAnEducation.from_json(json)
# print the JSON string representation of the object
print(DeleteAnEducation.to_json())

# convert the object into a dict
delete_an_education_dict = delete_an_education_instance.to_dict()
# create an instance of DeleteAnEducation from a dict
delete_an_education_from_dict = DeleteAnEducation.from_dict(delete_an_education_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


