# OpenToWorkWorkplaceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The type of workplace. | 
**location** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getclassicsearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values. | 

## Example

```python
from unipile.models.open_to_work_workplace_inner import OpenToWorkWorkplaceInner

# TODO update the JSON string below
json = "{}"
# create an instance of OpenToWorkWorkplaceInner from a JSON string
open_to_work_workplace_inner_instance = OpenToWorkWorkplaceInner.from_json(json)
# print the JSON string representation of the object
print(OpenToWorkWorkplaceInner.to_json())

# convert the object into a dict
open_to_work_workplace_inner_dict = open_to_work_workplace_inner_instance.to_dict()
# create an instance of OpenToWorkWorkplaceInner from a dict
open_to_work_workplace_inner_from_dict = OpenToWorkWorkplaceInner.from_dict(open_to_work_workplace_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


