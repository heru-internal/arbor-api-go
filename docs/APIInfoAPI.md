# \APIInfoAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetApiInfo**](APIInfoAPI.md#GetApiInfo) | **Get** / | 
[**GetTokenInfo**](APIInfoAPI.md#GetTokenInfo) | **Get** /token-info | 



## GetApiInfo

> GetApiInfo200Response GetApiInfo(ctx).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIInfoAPI.GetApiInfo(context.Background()).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIInfoAPI.GetApiInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetApiInfo`: GetApiInfo200Response
	fmt.Fprintf(os.Stdout, "Response from `APIInfoAPI.GetApiInfo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetApiInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

### Return type

[**GetApiInfo200Response**](GetApiInfo200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTokenInfo

> GetTokenInfo200Response GetTokenInfo(ctx).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIInfoAPI.GetTokenInfo(context.Background()).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIInfoAPI.GetTokenInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTokenInfo`: GetTokenInfo200Response
	fmt.Fprintf(os.Stdout, "Response from `APIInfoAPI.GetTokenInfo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTokenInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

### Return type

[**GetTokenInfo200Response**](GetTokenInfo200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

