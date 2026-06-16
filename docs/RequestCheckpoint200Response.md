# RequestCheckpoint200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**checkpoint** | [**CheckpointCheckpoint**](CheckpointCheckpoint.md) |  | 
**intent_id** | **str** | The ID of the auth intent. This should be used to listen for the QR Code scan with Solve Checkpoint. | 
**qrcode** | **str** | The QR Code to scan. | 

## Example

```python
from unipile.models.request_checkpoint200_response import RequestCheckpoint200Response

# TODO update the JSON string below
json = "{}"
# create an instance of RequestCheckpoint200Response from a JSON string
request_checkpoint200_response_instance = RequestCheckpoint200Response.from_json(json)
# print the JSON string representation of the object
print(RequestCheckpoint200Response.to_json())

# convert the object into a dict
request_checkpoint200_response_dict = request_checkpoint200_response_instance.to_dict()
# create an instance of RequestCheckpoint200Response from a dict
request_checkpoint200_response_from_dict = RequestCheckpoint200Response.from_dict(request_checkpoint200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


