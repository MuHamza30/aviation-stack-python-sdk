
# Custom Query Parameter



Documentation for accessing and setting credentials for ApiKeyAuth.

## Auth Credentials

| Name | Type | Description | Getter |
|  --- | --- | --- | --- |
| access_key | `str` | Your AviationStack API access key | `access_key` |



**Note:** Auth credentials can be set using `CustomQueryAuthenticationCredentials` object, passed in as named parameter `custom_query_authentication_credentials` in the client initialization.

## Usage Example

### Client Initialization

You must provide credentials in the client as shown in the following code snippet.

```python
from aviationstack.aviationstack_client import AviationstackClient
from aviationstack.http.auth.custom_query_authentication import CustomQueryAuthenticationCredentials

client = AviationstackClient(
    custom_query_authentication_credentials=CustomQueryAuthenticationCredentials(
        access_key='access_key'
    )
)
```


