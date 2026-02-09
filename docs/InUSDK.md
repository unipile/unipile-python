# InUSDK

Only available for jobs located in the US.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** |  | 
**starting_from** | **float** | The minimum amount. | 

## Example

```python
from unipile.models.in_usdk import InUSDK

# TODO update the JSON string below
json = "{}"
# create an instance of InUSDK from a JSON string
in_usdk_instance = InUSDK.from_json(json)
# print the JSON string representation of the object
print(InUSDK.to_json())

# convert the object into a dict
in_usdk_dict = in_usdk_instance.to_dict()
# create an instance of InUSDK from a dict
in_usdk_from_dict = InUSDK.from_dict(in_usdk_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


