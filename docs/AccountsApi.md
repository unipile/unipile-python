# unipile.AccountsApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_account**](AccountsApi.md#get_account) | **GET** /v2/accounts/{account_id} | Get an Account
[**list_accounts**](AccountsApi.md#list_accounts) | **GET** /v2/accounts/ | List all Accounts
[**remove_account**](AccountsApi.md#remove_account) | **DELETE** /v2/accounts/{account_id} | Remove an Account
[**update_account**](AccountsApi.md#update_account) | **PATCH** /v2/accounts/{account_id} | Update an Account


# **get_account**
> Account1 get_account(account_id)

Get an Account

Retrieve an Account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.account1 import Account1
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.AccountsApi(api_client)
    account_id = 'account_id_example' # str | 

    try:
        # Get an Account
        api_response = api_instance.get_account(account_id)
        print("The response of AccountsApi->get_account:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AccountsApi->get_account: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**|  | 

### Return type

[**Account1**](Account1.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_accounts**
> ListAccounts200Response list_accounts(status=status, provider=provider, search=search, offset=offset, limit=limit)

List all Accounts

Returns a list of all Accounts associated with the current Application. The accounts are returned sorted alphabeticaly on `name`.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_accounts200_response import ListAccounts200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.AccountsApi(api_client)
    status = 'status_example' # str | Filter to return only accounts of the given status. (optional)
    provider = 'provider_example' # str | Filter to return only accounts of the given provider.         - `mock` is mock.         - `whatsapp` is WhatsApp.         - `linkedin` is LinkedIn.         - `instagram` is Instagram.         - `google` is Google.         - `outlook` is Outlook.         - `telegram` is Telegram.         - `imap` is IMAP. (optional)
    search = 'search_example' # str | Filter to return only accounts matching the given search term on `name` or `id`. (optional)
    offset = 'offset_example' # str | An offset used for pagination. (optional)
    limit = '20' # str | The limit of items to be returned. (optional) (default to '20')

    try:
        # List all Accounts
        api_response = api_instance.list_accounts(status=status, provider=provider, search=search, offset=offset, limit=limit)
        print("The response of AccountsApi->list_accounts:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AccountsApi->list_accounts: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **str**| Filter to return only accounts of the given status. | [optional] 
 **provider** | **str**| Filter to return only accounts of the given provider.         - &#x60;mock&#x60; is mock.         - &#x60;whatsapp&#x60; is WhatsApp.         - &#x60;linkedin&#x60; is LinkedIn.         - &#x60;instagram&#x60; is Instagram.         - &#x60;google&#x60; is Google.         - &#x60;outlook&#x60; is Outlook.         - &#x60;telegram&#x60; is Telegram.         - &#x60;imap&#x60; is IMAP. | [optional] 
 **search** | **str**| Filter to return only accounts matching the given search term on &#x60;name&#x60; or &#x60;id&#x60;. | [optional] 
 **offset** | **str**| An offset used for pagination. | [optional] 
 **limit** | **str**| The limit of items to be returned. | [optional] [default to &#39;20&#39;]

### Return type

[**ListAccounts200Response**](ListAccounts200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **remove_account**
> RemoveAccount200Response remove_account(account_id)

Remove an Account

Remove an Account from Unipile by its ID. This action is irreversible and will remove all data associated with the Account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_account200_response import RemoveAccount200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.AccountsApi(api_client)
    account_id = 'account_id_example' # str | The ID of the Account to remove.

    try:
        # Remove an Account
        api_response = api_instance.remove_account(account_id)
        print("The response of AccountsApi->remove_account:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AccountsApi->remove_account: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| The ID of the Account to remove. | 

### Return type

[**RemoveAccount200Response**](RemoveAccount200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_account**
> Account1 update_account(account_id, update_account_request=update_account_request)

Update an Account

Update an Account by ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.account1 import Account1
from unipile.models.update_account_request import UpdateAccountRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.AccountsApi(api_client)
    account_id = 'account_id_example' # str | The ID of the Account to update.
    update_account_request = unipile.UpdateAccountRequest() # UpdateAccountRequest |  (optional)

    try:
        # Update an Account
        api_response = api_instance.update_account(account_id, update_account_request=update_account_request)
        print("The response of AccountsApi->update_account:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AccountsApi->update_account: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| The ID of the Account to update. | 
 **update_account_request** | [**UpdateAccountRequest**](UpdateAccountRequest.md)|  | [optional] 

### Return type

[**Account1**](Account1.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

