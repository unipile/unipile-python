# SubmitClassicCompanyOtpCodeRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | The email address on which you received the code. | 
**code** | **str** | The code that has been sent to you on the provided email address. | 
**challenge_id** | **str** | The challenge ID that you got from member verification response. | 

## Example

```python
from unipile.models.submit_classic_company_otp_code_request import SubmitClassicCompanyOtpCodeRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SubmitClassicCompanyOtpCodeRequest from a JSON string
submit_classic_company_otp_code_request_instance = SubmitClassicCompanyOtpCodeRequest.from_json(json)
# print the JSON string representation of the object
print(SubmitClassicCompanyOtpCodeRequest.to_json())

# convert the object into a dict
submit_classic_company_otp_code_request_dict = submit_classic_company_otp_code_request_instance.to_dict()
# create an instance of SubmitClassicCompanyOtpCodeRequest from a dict
submit_classic_company_otp_code_request_from_dict = SubmitClassicCompanyOtpCodeRequest.from_dict(submit_classic_company_otp_code_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


