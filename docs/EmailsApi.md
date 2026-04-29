# unipile.EmailsApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_draft**](EmailsApi.md#create_draft) | **POST** /v2/{account_id}/drafts | Create a Draft
[**create_folder**](EmailsApi.md#create_folder) | **POST** /v2/{account_id}/folders | Create a Folder
[**delete_draft**](EmailsApi.md#delete_draft) | **DELETE** /v2/{account_id}/drafts/{draft_id} | Delete a Draft
[**delete_folder**](EmailsApi.md#delete_folder) | **DELETE** /v2/{account_id}/folders/{folder_id} | Delete a Folder
[**get_attachment1**](EmailsApi.md#get_attachment1) | **GET** /v2/{account_id}/emails/{email_id}/attachments/{attachment_id} | Get an Email Attachment
[**get_draft**](EmailsApi.md#get_draft) | **GET** /v2/{account_id}/drafts/{draft_id} | Get a Draft
[**get_drafts_list**](EmailsApi.md#get_drafts_list) | **GET** /v2/{account_id}/drafts | List all Drafts
[**get_email**](EmailsApi.md#get_email) | **GET** /v2/{account_id}/emails/{email_id} | Get an Email
[**get_email_contacts_list**](EmailsApi.md#get_email_contacts_list) | **GET** /v2/{account_id}/contacts | List email contacts
[**get_emails_list**](EmailsApi.md#get_emails_list) | **GET** /v2/{account_id}/emails | List all Emails
[**get_folder**](EmailsApi.md#get_folder) | **GET** /v2/{account_id}/folders/{folder_id} | Get a Folder
[**get_folder_emails_list**](EmailsApi.md#get_folder_emails_list) | **GET** /v2/{account_id}/folders/{folder_id}/emails | List folder Emails
[**get_folders_list**](EmailsApi.md#get_folders_list) | **GET** /v2/{account_id}/folders | List all Folders
[**get_thread**](EmailsApi.md#get_thread) | **GET** /v2/{account_id}/threads/{thread_id} | Get a Thread
[**modify_email**](EmailsApi.md#modify_email) | **POST** /v2/{account_id}/emails/{email_id}/modify | Modify an Email
[**read_email**](EmailsApi.md#read_email) | **POST** /v2/{account_id}/emails/{email_id}/read | Read an Email
[**send_draft**](EmailsApi.md#send_draft) | **POST** /v2/{account_id}/drafts/{draft_id}/send | Send a Draft
[**send_email**](EmailsApi.md#send_email) | **POST** /v2/{account_id}/emails/send | Send an Email
[**trash_email**](EmailsApi.md#trash_email) | **DELETE** /v2/{account_id}/emails/{email_id} | Trash an Email
[**unread_email**](EmailsApi.md#unread_email) | **POST** /v2/{account_id}/emails/{email_id}/unread | Unread an Email
[**update_draft**](EmailsApi.md#update_draft) | **PATCH** /v2/{account_id}/drafts/{draft_id} | Update a Draft
[**update_folder**](EmailsApi.md#update_folder) | **PATCH** /v2/{account_id}/folders/{folder_id} | Update a Folder


# **create_draft**
> CreateDraft201Response create_draft(account_id, create_draft_request)

Create a Draft

Creates a new Draft in the draft folder of the provider. Use <a href="@todo">Send a Draft</a> to send the Email later.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_draft201_response import CreateDraft201Response
from unipile.models.create_draft_request import CreateDraftRequest
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
    api_instance = unipile.EmailsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_draft_request = unipile.CreateDraftRequest() # CreateDraftRequest | 

    try:
        # Create a Draft
        api_response = api_instance.create_draft(account_id, create_draft_request)
        print("The response of EmailsApi->create_draft:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->create_draft: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_draft_request** | [**CreateDraftRequest**](CreateDraftRequest.md)|  | 

### Return type

[**CreateDraft201Response**](CreateDraft201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_folder**
> CreateFolder201Response create_folder(account_id, create_folder_request)

Create a Folder

Creates a new Folder in the account mailbox.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_folder201_response import CreateFolder201Response
from unipile.models.create_folder_request import CreateFolderRequest
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
    api_instance = unipile.EmailsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_folder_request = unipile.CreateFolderRequest() # CreateFolderRequest | 

    try:
        # Create a Folder
        api_response = api_instance.create_folder(account_id, create_folder_request)
        print("The response of EmailsApi->create_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->create_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_folder_request** | [**CreateFolderRequest**](CreateFolderRequest.md)|  | 

### Return type

[**CreateFolder201Response**](CreateFolder201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_draft**
> delete_draft(draft_id, account_id)

Delete a Draft

Permanently deletes the specified Draft.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
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
    api_instance = unipile.EmailsApi(api_client)
    draft_id = 'draft_id_example' # str | 
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Draft
        api_instance.delete_draft(draft_id, account_id)
    except Exception as e:
        print("Exception when calling EmailsApi->delete_draft: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **draft_id** | **str**|  | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_folder**
> delete_folder(folder_id, account_id)

Delete a Folder

Deletes the specified Folder

### Example

* Api Key Authentication (apiKey):

```python
import unipile
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
    api_instance = unipile.EmailsApi(api_client)
    folder_id = 'folder_id_example' # str | ID of the Folder / Label to delete.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Folder
        api_instance.delete_folder(folder_id, account_id)
    except Exception as e:
        print("Exception when calling EmailsApi->delete_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **folder_id** | **str**| ID of the Folder / Label to delete. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_attachment1**
> get_attachment1(email_id, attachment_id, account_id)

Get an Email Attachment

Download the attachment file of an Email.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
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
    api_instance = unipile.EmailsApi(api_client)
    email_id = 'email_id_example' # str | ID of the parent Email.
    attachment_id = 'attachment_id_example' # str | ID of the Email Attachment to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get an Email Attachment
        api_instance.get_attachment1(email_id, attachment_id, account_id)
    except Exception as e:
        print("Exception when calling EmailsApi->get_attachment1: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email_id** | **str**| ID of the parent Email. | 
 **attachment_id** | **str**| ID of the Email Attachment to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_draft**
> CreateDraft201Response get_draft(draft_id, account_id)

Get a Draft

Retrieve the specified Draft.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_draft201_response import CreateDraft201Response
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
    api_instance = unipile.EmailsApi(api_client)
    draft_id = 'draft_id_example' # str | 
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Draft
        api_response = api_instance.get_draft(draft_id, account_id)
        print("The response of EmailsApi->get_draft:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_draft: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **draft_id** | **str**|  | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**CreateDraft201Response**](CreateDraft201Response.md)

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

# **get_drafts_list**
> GetDraftsList200Response get_drafts_list(account_id, to=to, var_from=var_from, any_email=any_email, offset=offset, limit=limit, cursor=cursor)

List all Drafts

Returns a list of the account drafts. Drafts are returned sorted by their creation date, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_drafts_list200_response import GetDraftsList200Response
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
    api_instance = unipile.EmailsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    to = 'to_example' # str | Filter to only return drafts with the given email address in to, cc or bcc field. (optional)
    var_from = 'var_from_example' # str | Filter to only return drafts  with the given email address in from. (optional)
    any_email = 'any_email_example' # str | Filter to only return drafts related to a comma-separated list of email addresses. (optional)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Drafts
        api_response = api_instance.get_drafts_list(account_id, to=to, var_from=var_from, any_email=any_email, offset=offset, limit=limit, cursor=cursor)
        print("The response of EmailsApi->get_drafts_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_drafts_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **to** | **str**| Filter to only return drafts with the given email address in to, cc or bcc field. | [optional] 
 **var_from** | **str**| Filter to only return drafts  with the given email address in from. | [optional] 
 **any_email** | **str**| Filter to only return drafts related to a comma-separated list of email addresses. | [optional] 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetDraftsList200Response**](GetDraftsList200Response.md)

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

# **get_email**
> GetThread200ResponseEmailsInner get_email(email_id, account_id, meta_only=meta_only)

Get an Email

Retrieve the specified Email.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_thread200_response_emails_inner import GetThread200ResponseEmailsInner
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
    api_instance = unipile.EmailsApi(api_client)
    email_id = 'email_id_example' # str | ID of the Email to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    meta_only = False # bool | Speed up the response by only returning the email metadata, excluding the body and attachments metadata. (optional) (default to False)

    try:
        # Get an Email
        api_response = api_instance.get_email(email_id, account_id, meta_only=meta_only)
        print("The response of EmailsApi->get_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email_id** | **str**| ID of the Email to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **meta_only** | **bool**| Speed up the response by only returning the email metadata, excluding the body and attachments metadata. | [optional] [default to False]

### Return type

[**GetThread200ResponseEmailsInner**](GetThread200ResponseEmailsInner.md)

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

# **get_email_contacts_list**
> GetEmailContactsList200Response get_email_contacts_list(account_id, cursor=cursor, limit=limit)

List email contacts

Returns a list of contacts from the email provider.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_email_contacts_list200_response import GetEmailContactsList200Response
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
    api_instance = unipile.EmailsApi(api_client)
    account_id = 'account_id_example' # str | 
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # List email contacts
        api_response = api_instance.get_email_contacts_list(account_id, cursor=cursor, limit=limit)
        print("The response of EmailsApi->get_email_contacts_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_email_contacts_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**|  | 
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**GetEmailContactsList200Response**](GetEmailContactsList200Response.md)

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

# **get_emails_list**
> GetEmailsList200Response get_emails_list(account_id, to=to, subject=subject, var_from=var_from, any_email=any_email, before=before, exclude_folder=exclude_folder, after=after, meta_only=meta_only, offset=offset, limit=limit, cursor=cursor)

List all Emails

Returns a list of emails in the account mailbox. Emails are returned sorted by their `date`, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_emails_list200_response import GetEmailsList200Response
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
    api_instance = unipile.EmailsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    to = 'to_example' # str | Filter to only return emails sent to the given email address, either in the to, cc or bcc field. (optional)
    subject = 'subject_example' # str | Filter to only return emails with the given string in the subject. (optional)
    var_from = 'var_from_example' # str | Filter to only return emails sent from the given email address. (optional)
    any_email = 'any_email_example' # str | Filter to only return emails related to a comma-separated list of email addresses. (optional)
    before = 'before_example' # str | Filter to only return emails sent before the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. (optional)
    exclude_folder = 'exclude_folder_example' # str | Filter to only return emails that are not in any of the folders specified in the comma-separated list of folder IDs. (optional)
    after = 'after_example' # str | Filter to only return emails sent after the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. (optional)
    meta_only = False # bool | Speed up the response by only returning the email metadata, excluding the body and attachments metadata. (optional) (default to False)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Emails
        api_response = api_instance.get_emails_list(account_id, to=to, subject=subject, var_from=var_from, any_email=any_email, before=before, exclude_folder=exclude_folder, after=after, meta_only=meta_only, offset=offset, limit=limit, cursor=cursor)
        print("The response of EmailsApi->get_emails_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_emails_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **to** | **str**| Filter to only return emails sent to the given email address, either in the to, cc or bcc field. | [optional] 
 **subject** | **str**| Filter to only return emails with the given string in the subject. | [optional] 
 **var_from** | **str**| Filter to only return emails sent from the given email address. | [optional] 
 **any_email** | **str**| Filter to only return emails related to a comma-separated list of email addresses. | [optional] 
 **before** | **str**| Filter to only return emails sent before the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. | [optional] 
 **exclude_folder** | **str**| Filter to only return emails that are not in any of the folders specified in the comma-separated list of folder IDs. | [optional] 
 **after** | **str**| Filter to only return emails sent after the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. | [optional] 
 **meta_only** | **bool**| Speed up the response by only returning the email metadata, excluding the body and attachments metadata. | [optional] [default to False]
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetEmailsList200Response**](GetEmailsList200Response.md)

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

# **get_folder**
> GetFoldersList200ResponseDataInner get_folder(folder_id, account_id)

Get a Folder

Retrieves the specified Folder

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_folders_list200_response_data_inner import GetFoldersList200ResponseDataInner
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
    api_instance = unipile.EmailsApi(api_client)
    folder_id = 'folder_id_example' # str | ID of the Folder / Label to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Folder
        api_response = api_instance.get_folder(folder_id, account_id)
        print("The response of EmailsApi->get_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **folder_id** | **str**| ID of the Folder / Label to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetFoldersList200ResponseDataInner**](GetFoldersList200ResponseDataInner.md)

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

# **get_folder_emails_list**
> GetEmailsList200Response get_folder_emails_list(folder_id, account_id, to=to, subject=subject, var_from=var_from, any_email=any_email, before=before, exclude_folder=exclude_folder, after=after, meta_only=meta_only, offset=offset, limit=limit, cursor=cursor)

List folder Emails

Returns a list of emails in the specific folder of the account mailbox. Emails are returned sorted by their `date`, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_emails_list200_response import GetEmailsList200Response
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
    api_instance = unipile.EmailsApi(api_client)
    folder_id = 'folder_id_example' # str | ID of the Folder to retrieve emails from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    to = 'to_example' # str | Filter to only return emails sent to the given email address, either in the to, cc or bcc field. (optional)
    subject = 'subject_example' # str | Filter to only return emails with the given string in the subject. (optional)
    var_from = 'var_from_example' # str | Filter to only return emails sent from the given email address. (optional)
    any_email = 'any_email_example' # str | Filter to only return emails related to a comma-separated list of email addresses. (optional)
    before = 'before_example' # str | Filter to only return emails sent before the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. (optional)
    exclude_folder = 'exclude_folder_example' # str | Filter to only return emails that are not in any of the folders specified in the comma-separated list of folder IDs. (optional)
    after = 'after_example' # str | Filter to only return emails sent after the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. (optional)
    meta_only = False # bool | Speed up the response by only returning the email metadata, excluding the body and attachments metadata. (optional) (default to False)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List folder Emails
        api_response = api_instance.get_folder_emails_list(folder_id, account_id, to=to, subject=subject, var_from=var_from, any_email=any_email, before=before, exclude_folder=exclude_folder, after=after, meta_only=meta_only, offset=offset, limit=limit, cursor=cursor)
        print("The response of EmailsApi->get_folder_emails_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_folder_emails_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **folder_id** | **str**| ID of the Folder to retrieve emails from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **to** | **str**| Filter to only return emails sent to the given email address, either in the to, cc or bcc field. | [optional] 
 **subject** | **str**| Filter to only return emails with the given string in the subject. | [optional] 
 **var_from** | **str**| Filter to only return emails sent from the given email address. | [optional] 
 **any_email** | **str**| Filter to only return emails related to a comma-separated list of email addresses. | [optional] 
 **before** | **str**| Filter to only return emails sent before the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. | [optional] 
 **exclude_folder** | **str**| Filter to only return emails that are not in any of the folders specified in the comma-separated list of folder IDs. | [optional] 
 **after** | **str**| Filter to only return emails sent after the given datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). For Gmail, only the date is used, the time is ignored. | [optional] 
 **meta_only** | **bool**| Speed up the response by only returning the email metadata, excluding the body and attachments metadata. | [optional] [default to False]
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetEmailsList200Response**](GetEmailsList200Response.md)

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

# **get_folders_list**
> GetFoldersList200Response get_folders_list(account_id, offset=offset, limit=limit, cursor=cursor)

List all Folders

Returns a list of folders in the account mailbox.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_folders_list200_response import GetFoldersList200Response
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
    api_instance = unipile.EmailsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Folders
        api_response = api_instance.get_folders_list(account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of EmailsApi->get_folders_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_folders_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetFoldersList200Response**](GetFoldersList200Response.md)

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

# **get_thread**
> GetThread200Response get_thread(thread_id, account_id, meta_only=meta_only)

Get a Thread

Returns a list of emails belonging to the specific thread. Emails are returned sorted by their `date`, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_thread200_response import GetThread200Response
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
    api_instance = unipile.EmailsApi(api_client)
    thread_id = 'thread_id_example' # str | ID of the Thread to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    meta_only = False # bool | Speed up the response by only returning the email metadata, excluding the body and attachments metadata. (optional) (default to False)

    try:
        # Get a Thread
        api_response = api_instance.get_thread(thread_id, account_id, meta_only=meta_only)
        print("The response of EmailsApi->get_thread:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->get_thread: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **thread_id** | **str**| ID of the Thread to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **meta_only** | **bool**| Speed up the response by only returning the email metadata, excluding the body and attachments metadata. | [optional] [default to False]

### Return type

[**GetThread200Response**](GetThread200Response.md)

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

# **modify_email**
> GetThread200ResponseEmailsInner modify_email(email_id, account_id, modify_email_request=modify_email_request)

Modify an Email

Modifies the folder(s) and/or provider-specific properties on the specified Email.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_thread200_response_emails_inner import GetThread200ResponseEmailsInner
from unipile.models.modify_email_request import ModifyEmailRequest
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
    api_instance = unipile.EmailsApi(api_client)
    email_id = 'email_id_example' # str | ID of the Email to modify.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    modify_email_request = unipile.ModifyEmailRequest() # ModifyEmailRequest |  (optional)

    try:
        # Modify an Email
        api_response = api_instance.modify_email(email_id, account_id, modify_email_request=modify_email_request)
        print("The response of EmailsApi->modify_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->modify_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email_id** | **str**| ID of the Email to modify. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **modify_email_request** | [**ModifyEmailRequest**](ModifyEmailRequest.md)|  | [optional] 

### Return type

[**GetThread200ResponseEmailsInner**](GetThread200ResponseEmailsInner.md)

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

# **read_email**
> ReadEmail200Response read_email(email_id, account_id)

Read an Email

Mark the specified Email as read.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.read_email200_response import ReadEmail200Response
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
    api_instance = unipile.EmailsApi(api_client)
    email_id = 'email_id_example' # str | ID of the Email to mark as read.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Read an Email
        api_response = api_instance.read_email(email_id, account_id)
        print("The response of EmailsApi->read_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->read_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email_id** | **str**| ID of the Email to mark as read. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**ReadEmail200Response**](ReadEmail200Response.md)

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

# **send_draft**
> SendEmail200Response send_draft(draft_id, account_id)

Send a Draft

Sends the specified Draft to the recipients in the `to`, `cc`, and `bcc` fields of the draft.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.send_email200_response import SendEmail200Response
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
    api_instance = unipile.EmailsApi(api_client)
    draft_id = 'draft_id_example' # str | ID of the draft to send.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Send a Draft
        api_response = api_instance.send_draft(draft_id, account_id)
        print("The response of EmailsApi->send_draft:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->send_draft: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **draft_id** | **str**| ID of the draft to send. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**SendEmail200Response**](SendEmail200Response.md)

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

# **send_email**
> SendEmail200Response send_email(account_id, send_email_request)

Send an Email

Sends an Email to the recipients in the `to`, `cc`, and `bcc`.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.send_email200_response import SendEmail200Response
from unipile.models.send_email_request import SendEmailRequest
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
    api_instance = unipile.EmailsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    send_email_request = unipile.SendEmailRequest() # SendEmailRequest | 

    try:
        # Send an Email
        api_response = api_instance.send_email(account_id, send_email_request)
        print("The response of EmailsApi->send_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->send_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **send_email_request** | [**SendEmailRequest**](SendEmailRequest.md)|  | 

### Return type

[**SendEmail200Response**](SendEmail200Response.md)

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

# **trash_email**
> TrashEmail200Response trash_email(email_id, account_id)

Trash an Email

Moves the specified Email to the trash.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.trash_email200_response import TrashEmail200Response
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
    api_instance = unipile.EmailsApi(api_client)
    email_id = 'email_id_example' # str | ID of the Email to trash.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Trash an Email
        api_response = api_instance.trash_email(email_id, account_id)
        print("The response of EmailsApi->trash_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->trash_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email_id** | **str**| ID of the Email to trash. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**TrashEmail200Response**](TrashEmail200Response.md)

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

# **unread_email**
> UnreadEmail200Response unread_email(email_id, account_id)

Unread an Email

Mark the specified Email as unread.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.unread_email200_response import UnreadEmail200Response
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
    api_instance = unipile.EmailsApi(api_client)
    email_id = 'email_id_example' # str | ID of the Email to mark as unread.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Unread an Email
        api_response = api_instance.unread_email(email_id, account_id)
        print("The response of EmailsApi->unread_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->unread_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email_id** | **str**| ID of the Email to mark as unread. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**UnreadEmail200Response**](UnreadEmail200Response.md)

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

# **update_draft**
> CreateDraft201Response update_draft(draft_id, account_id, update_draft_request=update_draft_request)

Update a Draft

Updates the specified Draft by setting the values of the parameters passed. Any parameters not provided will be left unchanged.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_draft201_response import CreateDraft201Response
from unipile.models.update_draft_request import UpdateDraftRequest
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
    api_instance = unipile.EmailsApi(api_client)
    draft_id = 'draft_id_example' # str | 
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_draft_request = unipile.UpdateDraftRequest() # UpdateDraftRequest |  (optional)

    try:
        # Update a Draft
        api_response = api_instance.update_draft(draft_id, account_id, update_draft_request=update_draft_request)
        print("The response of EmailsApi->update_draft:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->update_draft: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **draft_id** | **str**|  | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_draft_request** | [**UpdateDraftRequest**](UpdateDraftRequest.md)|  | [optional] 

### Return type

[**CreateDraft201Response**](CreateDraft201Response.md)

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

# **update_folder**
> GetFoldersList200ResponseDataInner update_folder(folder_id, account_id, update_folder_request=update_folder_request)

Update a Folder

Updates the specified Folder by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_folders_list200_response_data_inner import GetFoldersList200ResponseDataInner
from unipile.models.update_folder_request import UpdateFolderRequest
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
    api_instance = unipile.EmailsApi(api_client)
    folder_id = 'folder_id_example' # str | ID of the Folder / Label to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_folder_request = unipile.UpdateFolderRequest() # UpdateFolderRequest |  (optional)

    try:
        # Update a Folder
        api_response = api_instance.update_folder(folder_id, account_id, update_folder_request=update_folder_request)
        print("The response of EmailsApi->update_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EmailsApi->update_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **folder_id** | **str**| ID of the Folder / Label to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_folder_request** | [**UpdateFolderRequest**](UpdateFolderRequest.md)|  | [optional] 

### Return type

[**GetFoldersList200ResponseDataInner**](GetFoldersList200ResponseDataInner.md)

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

