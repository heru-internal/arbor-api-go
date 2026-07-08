# \AppBundlesAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddFilesToAppBundle**](AppBundlesAPI.md#AddFilesToAppBundle) | **Post** /app-bundles/{appBundleId}/files | 
[**CreateAppBundle**](AppBundlesAPI.md#CreateAppBundle) | **Post** /app-bundles | 
[**FinalizeAppBundle**](AppBundlesAPI.md#FinalizeAppBundle) | **Post** /app-bundles/{appBundleId}/finalize | 
[**GetAppBundle**](AppBundlesAPI.md#GetAppBundle) | **Get** /app-bundles/{appBundleId} | 
[**GetAppBundleFiles**](AppBundlesAPI.md#GetAppBundleFiles) | **Get** /app-bundles/{appBundleId}/files | 
[**UpdateAppBundle**](AppBundlesAPI.md#UpdateAppBundle) | **Patch** /app-bundles/{appBundleId} | 



## AddFilesToAppBundle

> CreateAppBundle201Response AddFilesToAppBundle(ctx, appBundleId).Accept(accept).AddFilesToAppBundleRequest(addFilesToAppBundleRequest).Execute()





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
	appBundleId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app bundle.
	addFilesToAppBundleRequest := *openapiclient.NewAddFilesToAppBundleRequest([]openapiclient.CreateAppBundleRequestFilesInner{*openapiclient.NewCreateAppBundleRequestFilesInner("789e1234-e89b-12d3-a456-426614174000")}) // AddFilesToAppBundleRequest | Files to add to the app bundle (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppBundlesAPI.AddFilesToAppBundle(context.Background(), appBundleId).Accept(accept).AddFilesToAppBundleRequest(addFilesToAppBundleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppBundlesAPI.AddFilesToAppBundle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddFilesToAppBundle`: CreateAppBundle201Response
	fmt.Fprintf(os.Stdout, "Response from `AppBundlesAPI.AddFilesToAppBundle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appBundleId** | **string** | The ID of an app bundle. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddFilesToAppBundleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **addFilesToAppBundleRequest** | [**AddFilesToAppBundleRequest**](AddFilesToAppBundleRequest.md) | Files to add to the app bundle | 

### Return type

[**CreateAppBundle201Response**](CreateAppBundle201Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAppBundle

> CreateAppBundle201Response CreateAppBundle(ctx).Accept(accept).CreateAppBundleRequest(createAppBundleRequest).Execute()





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
	createAppBundleRequest := *openapiclient.NewCreateAppBundleRequest("550e8400-e29b-41d4-a716-446655440000") // CreateAppBundleRequest | Create a new app bundle from existing build and files. Labels are auto-generated. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppBundlesAPI.CreateAppBundle(context.Background()).Accept(accept).CreateAppBundleRequest(createAppBundleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppBundlesAPI.CreateAppBundle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppBundle`: CreateAppBundle201Response
	fmt.Fprintf(os.Stdout, "Response from `AppBundlesAPI.CreateAppBundle`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppBundleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **createAppBundleRequest** | [**CreateAppBundleRequest**](CreateAppBundleRequest.md) | Create a new app bundle from existing build and files. Labels are auto-generated. | 

### Return type

[**CreateAppBundle201Response**](CreateAppBundle201Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FinalizeAppBundle

> CreateAppBundle201Response FinalizeAppBundle(ctx, appBundleId).Accept(accept).Execute()





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
	appBundleId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app bundle.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppBundlesAPI.FinalizeAppBundle(context.Background(), appBundleId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppBundlesAPI.FinalizeAppBundle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FinalizeAppBundle`: CreateAppBundle201Response
	fmt.Fprintf(os.Stdout, "Response from `AppBundlesAPI.FinalizeAppBundle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appBundleId** | **string** | The ID of an app bundle. | 

### Other Parameters

Other parameters are passed through a pointer to a apiFinalizeAppBundleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**CreateAppBundle201Response**](CreateAppBundle201Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppBundle

> CreateAppBundle201Response GetAppBundle(ctx, appBundleId).Accept(accept).Execute()





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
	appBundleId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app bundle.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppBundlesAPI.GetAppBundle(context.Background(), appBundleId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppBundlesAPI.GetAppBundle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppBundle`: CreateAppBundle201Response
	fmt.Fprintf(os.Stdout, "Response from `AppBundlesAPI.GetAppBundle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appBundleId** | **string** | The ID of an app bundle. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppBundleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**CreateAppBundle201Response**](CreateAppBundle201Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppBundleFiles

> GetAppBundleFiles200Response GetAppBundleFiles(ctx, appBundleId).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	appBundleId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app bundle.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppBundlesAPI.GetAppBundleFiles(context.Background(), appBundleId).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppBundlesAPI.GetAppBundleFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppBundleFiles`: GetAppBundleFiles200Response
	fmt.Fprintf(os.Stdout, "Response from `AppBundlesAPI.GetAppBundleFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appBundleId** | **string** | The ID of an app bundle. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppBundleFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetAppBundleFiles200Response**](GetAppBundleFiles200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppBundle

> CreateAppBundle201Response UpdateAppBundle(ctx, appBundleId).Accept(accept).UpdateAppBundleRequest(updateAppBundleRequest).Execute()





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
	appBundleId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app bundle.
	updateAppBundleRequest := *openapiclient.NewUpdateAppBundleRequest() // UpdateAppBundleRequest | Update an app bundle's label. Set to null to remove the label. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppBundlesAPI.UpdateAppBundle(context.Background(), appBundleId).Accept(accept).UpdateAppBundleRequest(updateAppBundleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppBundlesAPI.UpdateAppBundle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppBundle`: CreateAppBundle201Response
	fmt.Fprintf(os.Stdout, "Response from `AppBundlesAPI.UpdateAppBundle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appBundleId** | **string** | The ID of an app bundle. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppBundleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **updateAppBundleRequest** | [**UpdateAppBundleRequest**](UpdateAppBundleRequest.md) | Update an app bundle&#39;s label. Set to null to remove the label. | 

### Return type

[**CreateAppBundle201Response**](CreateAppBundle201Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

