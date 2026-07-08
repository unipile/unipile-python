# LinkedIn1ConfigProducts

Specifies which LinkedIn products to activate. For the premium `recruiter` and `sales_navigator` products, only one can be activated per account. Also, if the account does not have an active subscription, the linking will fail.<br>When reconnecting an account, just omit this field to keep connecting the same products, or provide new values to expand or narrow the products scope. <a href=\"https://developer.unipile.com/v2.0/docs/linkedin-link-accounts\">Learn more about Linkedin products</a>       `classic` : LinkedIn Social network<br>       `recruiter` : Recruiter<br>       `sales_navigator` : Sales navigator<br>       `company` : Company Pages       

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.linked_in1_config_products import LinkedIn1ConfigProducts

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1ConfigProducts from a JSON string
linked_in1_config_products_instance = LinkedIn1ConfigProducts.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1ConfigProducts.to_json())

# convert the object into a dict
linked_in1_config_products_dict = linked_in1_config_products_instance.to_dict()
# create an instance of LinkedIn1ConfigProducts from a dict
linked_in1_config_products_from_dict = LinkedIn1ConfigProducts.from_dict(linked_in1_config_products_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


