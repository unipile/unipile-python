# QRCode

The authentication was started for a QR Code.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**qrcode** | **str** | The QR Code to scan. | 
**intent_id** | **str** | The ID of the auth intent. This should be used to listen for the QR Code scan with Solve Checkpoint. | 

## Example

```python
from unipile.models.qr_code import QRCode

# TODO update the JSON string below
json = "{}"
# create an instance of QRCode from a JSON string
qr_code_instance = QRCode.from_json(json)
# print the JSON string representation of the object
print(QRCode.to_json())

# convert the object into a dict
qr_code_dict = qr_code_instance.to_dict()
# create an instance of QRCode from a dict
qr_code_from_dict = QRCode.from_dict(qr_code_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


