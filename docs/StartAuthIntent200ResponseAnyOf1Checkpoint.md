# StartAuthIntent200ResponseAnyOf1Checkpoint


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**extension_code** | **str** |  | 
**extension_code_expires_at** | **datetime** |  | 
**expires_at** | **datetime** |  | 
**extension_store_urls** | [**StartAuthIntent200ResponseAnyOf1CheckpointExtensionStoreUrls**](StartAuthIntent200ResponseAnyOf1CheckpointExtensionStoreUrls.md) |  | 
**extension_download_urls** | [**StartAuthIntent200ResponseAnyOf1CheckpointExtensionDownloadUrls**](StartAuthIntent200ResponseAnyOf1CheckpointExtensionDownloadUrls.md) |  | 

## Example

```python
from unipile.models.start_auth_intent200_response_any_of1_checkpoint import StartAuthIntent200ResponseAnyOf1Checkpoint

# TODO update the JSON string below
json = "{}"
# create an instance of StartAuthIntent200ResponseAnyOf1Checkpoint from a JSON string
start_auth_intent200_response_any_of1_checkpoint_instance = StartAuthIntent200ResponseAnyOf1Checkpoint.from_json(json)
# print the JSON string representation of the object
print(StartAuthIntent200ResponseAnyOf1Checkpoint.to_json())

# convert the object into a dict
start_auth_intent200_response_any_of1_checkpoint_dict = start_auth_intent200_response_any_of1_checkpoint_instance.to_dict()
# create an instance of StartAuthIntent200ResponseAnyOf1Checkpoint from a dict
start_auth_intent200_response_any_of1_checkpoint_from_dict = StartAuthIntent200ResponseAnyOf1Checkpoint.from_dict(start_auth_intent200_response_any_of1_checkpoint_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


