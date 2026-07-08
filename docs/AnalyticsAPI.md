# \AnalyticsAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAppSessions**](AnalyticsAPI.md#GetAppSessions) | **Get** /app-sessions/{appId} | 
[**GetAppUsage**](AnalyticsAPI.md#GetAppUsage) | **Get** /app-usage | 
[**GetDeviceSessions**](AnalyticsAPI.md#GetDeviceSessions) | **Get** /device-sessions/{deviceId} | 
[**GetSharedAppUsage**](AnalyticsAPI.md#GetSharedAppUsage) | **Get** /shared-app-usage/{appId} | 
[**GetSharedAppUsages**](AnalyticsAPI.md#GetSharedAppUsages) | **Get** /shared-app-usage | 



## GetAppSessions

> GetAppSessions200Response GetAppSessions(ctx, appId).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app.
	startDate := time.Now() // string | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	endDate := time.Now() // string | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetAppSessions(context.Background(), appId).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetAppSessions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppSessions`: GetAppSessions200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetAppSessions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** | The ID of an app. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppSessionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **startDate** | **string** | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **endDate** | **string** | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetAppSessions200Response**](GetAppSessions200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppUsage

> GetAppUsage200Response GetAppUsage(ctx).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	startDate := time.Now() // string | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	endDate := time.Now() // string | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetAppUsage(context.Background()).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetAppUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppUsage`: GetAppUsage200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetAppUsage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAppUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **startDate** | **string** | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **endDate** | **string** | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetAppUsage200Response**](GetAppUsage200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceSessions

> GetAppSessions200Response GetDeviceSessions(ctx, deviceId).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	startDate := time.Now() // string | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	endDate := time.Now() // string | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetDeviceSessions(context.Background(), deviceId).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetDeviceSessions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceSessions`: GetAppSessions200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetDeviceSessions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceSessionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **startDate** | **string** | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **endDate** | **string** | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetAppSessions200Response**](GetAppSessions200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSharedAppUsage

> GetAppUsage200ResponseDataInner GetSharedAppUsage(ctx, appId).Accept(accept).StartDate(startDate).EndDate(endDate).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app.
	startDate := time.Now() // string | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	endDate := time.Now() // string | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetSharedAppUsage(context.Background(), appId).Accept(accept).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetSharedAppUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSharedAppUsage`: GetAppUsage200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetSharedAppUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** | The ID of an app. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSharedAppUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **startDate** | **string** | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **endDate** | **string** | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 

### Return type

[**GetAppUsage200ResponseDataInner**](GetAppUsage200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSharedAppUsages

> GetAppUsage200Response GetSharedAppUsages(ctx).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	startDate := time.Now() // string | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	endDate := time.Now() // string | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD).
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetSharedAppUsages(context.Background()).Accept(accept).StartDate(startDate).EndDate(endDate).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetSharedAppUsages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSharedAppUsages`: GetAppUsage200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetSharedAppUsages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSharedAppUsagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **startDate** | **string** | The start date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **endDate** | **string** | The end date bound for the query, in ISO 8601 format (YYYY-MM-DD). | 
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetAppUsage200Response**](GetAppUsage200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

