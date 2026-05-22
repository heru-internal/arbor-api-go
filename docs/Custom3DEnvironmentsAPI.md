# \Custom3DEnvironmentsAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CompleteCustom3DEnvironmentUpload**](Custom3DEnvironmentsAPI.md#CompleteCustom3DEnvironmentUpload) | **Post** /custom-3d-environments/{custom3DEnvironmentId}/complete | 
[**GetCustom3DEnvironment**](Custom3DEnvironmentsAPI.md#GetCustom3DEnvironment) | **Get** /custom-3d-environments/{custom3DEnvironmentId} | 
[**GetCustom3DEnvironments**](Custom3DEnvironmentsAPI.md#GetCustom3DEnvironments) | **Get** /custom-3d-environments | 
[**InitiateCustom3DEnvironmentUpload**](Custom3DEnvironmentsAPI.md#InitiateCustom3DEnvironmentUpload) | **Post** /custom-3d-environments | 
[**PreSignCustom3DEnvironmentUpload**](Custom3DEnvironmentsAPI.md#PreSignCustom3DEnvironmentUpload) | **Post** /custom-3d-environments/{custom3DEnvironmentId}/pre-sign | 



## CompleteCustom3DEnvironmentUpload

> GetCustom3DEnvironment200Response CompleteCustom3DEnvironmentUpload(ctx, custom3DEnvironmentId).Accept(accept).CompleteCustom3DEnvironmentUploadRequest(completeCustom3DEnvironmentUploadRequest).Execute()





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
	custom3DEnvironmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the custom 3D environment.
	completeCustom3DEnvironmentUploadRequest := *openapiclient.NewCompleteCustom3DEnvironmentUploadRequest("custom-3d-environments%2F123e4567-e89b-12d3-a456-426614174000%2Fmy-environment.glb", "ExampleUploadId123", []openapiclient.CompleteCustom3DEnvironmentUploadRequestPartsInner{*openapiclient.NewCompleteCustom3DEnvironmentUploadRequestPartsInner(int32(123), "ETag_example")}) // CompleteCustom3DEnvironmentUploadRequest | Complete a multipart upload for a custom 3D environment. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.Custom3DEnvironmentsAPI.CompleteCustom3DEnvironmentUpload(context.Background(), custom3DEnvironmentId).Accept(accept).CompleteCustom3DEnvironmentUploadRequest(completeCustom3DEnvironmentUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `Custom3DEnvironmentsAPI.CompleteCustom3DEnvironmentUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompleteCustom3DEnvironmentUpload`: GetCustom3DEnvironment200Response
	fmt.Fprintf(os.Stdout, "Response from `Custom3DEnvironmentsAPI.CompleteCustom3DEnvironmentUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custom3DEnvironmentId** | **string** | The ID of the custom 3D environment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCompleteCustom3DEnvironmentUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **completeCustom3DEnvironmentUploadRequest** | [**CompleteCustom3DEnvironmentUploadRequest**](CompleteCustom3DEnvironmentUploadRequest.md) | Complete a multipart upload for a custom 3D environment. | 

### Return type

[**GetCustom3DEnvironment200Response**](GetCustom3DEnvironment200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCustom3DEnvironment

> GetCustom3DEnvironment200Response GetCustom3DEnvironment(ctx, custom3DEnvironmentId).Accept(accept).Execute()





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
	custom3DEnvironmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the custom 3D environment.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.Custom3DEnvironmentsAPI.GetCustom3DEnvironment(context.Background(), custom3DEnvironmentId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `Custom3DEnvironmentsAPI.GetCustom3DEnvironment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCustom3DEnvironment`: GetCustom3DEnvironment200Response
	fmt.Fprintf(os.Stdout, "Response from `Custom3DEnvironmentsAPI.GetCustom3DEnvironment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custom3DEnvironmentId** | **string** | The ID of the custom 3D environment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCustom3DEnvironmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetCustom3DEnvironment200Response**](GetCustom3DEnvironment200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCustom3DEnvironments

> GetCustom3DEnvironments200Response GetCustom3DEnvironments(ctx).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.Custom3DEnvironmentsAPI.GetCustom3DEnvironments(context.Background()).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `Custom3DEnvironmentsAPI.GetCustom3DEnvironments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCustom3DEnvironments`: GetCustom3DEnvironments200Response
	fmt.Fprintf(os.Stdout, "Response from `Custom3DEnvironmentsAPI.GetCustom3DEnvironments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCustom3DEnvironmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetCustom3DEnvironments200Response**](GetCustom3DEnvironments200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitiateCustom3DEnvironmentUpload

> InitiateCustom3DEnvironmentUpload201Response InitiateCustom3DEnvironmentUpload(ctx).Accept(accept).InitiateCustom3DEnvironmentUploadRequest(initiateCustom3DEnvironmentUploadRequest).Execute()





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
	initiateCustom3DEnvironmentUploadRequest := *openapiclient.NewInitiateCustom3DEnvironmentUploadRequest("my-environment.glb") // InitiateCustom3DEnvironmentUploadRequest | Initiate a new custom 3D environment upload. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.Custom3DEnvironmentsAPI.InitiateCustom3DEnvironmentUpload(context.Background()).Accept(accept).InitiateCustom3DEnvironmentUploadRequest(initiateCustom3DEnvironmentUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `Custom3DEnvironmentsAPI.InitiateCustom3DEnvironmentUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitiateCustom3DEnvironmentUpload`: InitiateCustom3DEnvironmentUpload201Response
	fmt.Fprintf(os.Stdout, "Response from `Custom3DEnvironmentsAPI.InitiateCustom3DEnvironmentUpload`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInitiateCustom3DEnvironmentUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **initiateCustom3DEnvironmentUploadRequest** | [**InitiateCustom3DEnvironmentUploadRequest**](InitiateCustom3DEnvironmentUploadRequest.md) | Initiate a new custom 3D environment upload. | 

### Return type

[**InitiateCustom3DEnvironmentUpload201Response**](InitiateCustom3DEnvironmentUpload201Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreSignCustom3DEnvironmentUpload

> []PreSignCustom3DEnvironmentUpload200ResponseInner PreSignCustom3DEnvironmentUpload(ctx, custom3DEnvironmentId).Accept(accept).PreSignCustom3DEnvironmentUploadRequest(preSignCustom3DEnvironmentUploadRequest).Execute()





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
	custom3DEnvironmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the custom 3D environment.
	preSignCustom3DEnvironmentUploadRequest := *openapiclient.NewPreSignCustom3DEnvironmentUploadRequest("custom-3d-environments%2F123e4567-e89b-12d3-a456-426614174000%2Fmy-environment.glb", "ExampleUploadId123", []int32{int32(123)}) // PreSignCustom3DEnvironmentUploadRequest | Pre-sign URLs for multipart upload parts. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.Custom3DEnvironmentsAPI.PreSignCustom3DEnvironmentUpload(context.Background(), custom3DEnvironmentId).Accept(accept).PreSignCustom3DEnvironmentUploadRequest(preSignCustom3DEnvironmentUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `Custom3DEnvironmentsAPI.PreSignCustom3DEnvironmentUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreSignCustom3DEnvironmentUpload`: []PreSignCustom3DEnvironmentUpload200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `Custom3DEnvironmentsAPI.PreSignCustom3DEnvironmentUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custom3DEnvironmentId** | **string** | The ID of the custom 3D environment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPreSignCustom3DEnvironmentUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **preSignCustom3DEnvironmentUploadRequest** | [**PreSignCustom3DEnvironmentUploadRequest**](PreSignCustom3DEnvironmentUploadRequest.md) | Pre-sign URLs for multipart upload parts. | 

### Return type

[**[]PreSignCustom3DEnvironmentUpload200ResponseInner**](PreSignCustom3DEnvironmentUpload200ResponseInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

