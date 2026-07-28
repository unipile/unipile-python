# LinkedIn2ConfigProducts

Specifies which LinkedIn products to activate. For the premium `recruiter` and `sales_navigator` products, only one can be activated per account. Also, if the account does not have an active subscription, the linking will fail.<br>When reconnecting an account, just omit this field to keep connecting the same products, or provide new values to expand or narrow the products scope. <a href=\"https://developer.unipile.com/v2.0/docs/linkedin-link-accounts\">Learn more about Linkedin products</a>       `classic` : LinkedIn Social network<br>       `recruiter` : Recruiter<br>       `sales_navigator` : Sales navigator<br>       `company` : Company Pages       

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.linked_in2_config_products import LinkedIn2ConfigProducts

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2ConfigProducts from a JSON string
linked_in2_config_products_instance = LinkedIn2ConfigProducts.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2ConfigProducts.to_json())

# convert the object into a dict
linked_in2_config_products_dict = linked_in2_config_products_instance.to_dict()
# create an instance of LinkedIn2ConfigProducts from a dict
linked_in2_config_products_from_dict = LinkedIn2ConfigProducts.from_dict(linked_in2_config_products_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


