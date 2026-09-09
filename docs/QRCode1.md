# QRCode1

Authenticate by scanning a QR code with the WhatsApp mobile app.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**qrcode** | **bool** | This must be set to &#x60;true&#x60; | 

## Example

```python
from unipile.models.qr_code1 import QRCode1

# TODO update the JSON string below
json = "{}"
# create an instance of QRCode1 from a JSON string
qr_code1_instance = QRCode1.from_json(json)
# print the JSON string representation of the object
print(QRCode1.to_json())

# convert the object into a dict
qr_code1_dict = qr_code1_instance.to_dict()
# create an instance of QRCode1 from a dict
qr_code1_from_dict = QRCode1.from_dict(qr_code1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


