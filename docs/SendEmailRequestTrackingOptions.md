# SendEmailRequestTrackingOptions

Configuration of tracking for this email.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**opens** | **bool** | If &#x60;true&#x60;, trigger webhooks listening to &#x60;tracking.open&#x60; when the email is opened by the recipient. | [optional] [default to False]
**links** | **bool** | If &#x60;true&#x60;, trigger webhooks listening to &#x60;tracking.link&#x60; when the recipient click on a link in the email content. | [optional] [default to False]
**label** | **str** | A label to be sent in the tracking event. This can help you to identify the sent email. | [optional] 
**custom_domain** | **str** | Your custom domain pointing to https://tracking.unipile.com to handle links tracking. | [optional] 

## Example

```python
from unipile.models.send_email_request_tracking_options import SendEmailRequestTrackingOptions

# TODO update the JSON string below
json = "{}"
# create an instance of SendEmailRequestTrackingOptions from a JSON string
send_email_request_tracking_options_instance = SendEmailRequestTrackingOptions.from_json(json)
# print the JSON string representation of the object
print(SendEmailRequestTrackingOptions.to_json())

# convert the object into a dict
send_email_request_tracking_options_dict = send_email_request_tracking_options_instance.to_dict()
# create an instance of SendEmailRequestTrackingOptions from a dict
send_email_request_tracking_options_from_dict = SendEmailRequestTrackingOptions.from_dict(send_email_request_tracking_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


