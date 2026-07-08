# \DeviceExperienceAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ConfigureDeviceDefaultHomeDeviceExperience**](DeviceExperienceAPI.md#ConfigureDeviceDefaultHomeDeviceExperience) | **Post** /devices/{deviceId}/device-experience/default-home | 
[**ConfigureDeviceInHouseLauncherDeviceExperience**](DeviceExperienceAPI.md#ConfigureDeviceInHouseLauncherDeviceExperience) | **Post** /devices/{deviceId}/device-experience/in-house-launcher | 
[**ConfigureDeviceLockTaskDeviceExperience**](DeviceExperienceAPI.md#ConfigureDeviceLockTaskDeviceExperience) | **Post** /devices/{deviceId}/device-experience/lock-task | 
[**ConfigureGroupDefaultHomeDeviceExperience**](DeviceExperienceAPI.md#ConfigureGroupDefaultHomeDeviceExperience) | **Post** /groups/{groupId}/device-experience/default-home | 
[**ConfigureGroupInHouseLauncherDeviceExperience**](DeviceExperienceAPI.md#ConfigureGroupInHouseLauncherDeviceExperience) | **Post** /groups/{groupId}/device-experience/in-house-launcher | 
[**ConfigureGroupLockTaskDeviceExperience**](DeviceExperienceAPI.md#ConfigureGroupLockTaskDeviceExperience) | **Post** /groups/{groupId}/device-experience/lock-task | 
[**GetDeviceDeviceExperience**](DeviceExperienceAPI.md#GetDeviceDeviceExperience) | **Get** /devices/{deviceId}/device-experience | 
[**GetGroupDeviceExperience**](DeviceExperienceAPI.md#GetGroupDeviceExperience) | **Get** /groups/{groupId}/device-experience | 



## ConfigureDeviceDefaultHomeDeviceExperience

> ConfigureDeviceDefaultHomeDeviceExperience(ctx, deviceId).Accept(accept).Body(body).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	body := map[string]interface{}{ ... } // map[string]interface{} | Request body for configuring the Default Home device experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceExperienceAPI.ConfigureDeviceDefaultHomeDeviceExperience(context.Background(), deviceId).Accept(accept).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.ConfigureDeviceDefaultHomeDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureDeviceDefaultHomeDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **body** | **map[string]interface{}** | Request body for configuring the Default Home device experience. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureDeviceInHouseLauncherDeviceExperience

> ConfigureDeviceInHouseLauncherDeviceExperience(ctx, deviceId).Accept(accept).ConfigureGroupInHouseLauncherDeviceExperienceRequest(configureGroupInHouseLauncherDeviceExperienceRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	configureGroupInHouseLauncherDeviceExperienceRequest := *openapiclient.NewConfigureGroupInHouseLauncherDeviceExperienceRequest(*openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner("Id_example", "Type_example"), []openapiclient.ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner("Id_example", "Type_example")}) // ConfigureGroupInHouseLauncherDeviceExperienceRequest | Request body for configuring the In-House Launcher device experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceExperienceAPI.ConfigureDeviceInHouseLauncherDeviceExperience(context.Background(), deviceId).Accept(accept).ConfigureGroupInHouseLauncherDeviceExperienceRequest(configureGroupInHouseLauncherDeviceExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.ConfigureDeviceInHouseLauncherDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureDeviceInHouseLauncherDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupInHouseLauncherDeviceExperienceRequest** | [**ConfigureGroupInHouseLauncherDeviceExperienceRequest**](ConfigureGroupInHouseLauncherDeviceExperienceRequest.md) | Request body for configuring the In-House Launcher device experience. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureDeviceLockTaskDeviceExperience

> ConfigureDeviceLockTaskDeviceExperience(ctx, deviceId).Accept(accept).ConfigureGroupLockTaskDeviceExperienceRequest(configureGroupLockTaskDeviceExperienceRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	configureGroupLockTaskDeviceExperienceRequest := *openapiclient.NewConfigureGroupLockTaskDeviceExperienceRequest([]openapiclient.ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner("Id_example", "Type_example")}) // ConfigureGroupLockTaskDeviceExperienceRequest | Request body for configuring the Lock Task device experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceExperienceAPI.ConfigureDeviceLockTaskDeviceExperience(context.Background(), deviceId).Accept(accept).ConfigureGroupLockTaskDeviceExperienceRequest(configureGroupLockTaskDeviceExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.ConfigureDeviceLockTaskDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureDeviceLockTaskDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupLockTaskDeviceExperienceRequest** | [**ConfigureGroupLockTaskDeviceExperienceRequest**](ConfigureGroupLockTaskDeviceExperienceRequest.md) | Request body for configuring the Lock Task device experience. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureGroupDefaultHomeDeviceExperience

> ConfigureGroupDefaultHomeDeviceExperience(ctx, groupId).Accept(accept).Body(body).Execute()





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
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	body := map[string]interface{}{ ... } // map[string]interface{} | Request body for configuring the Default Home device experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceExperienceAPI.ConfigureGroupDefaultHomeDeviceExperience(context.Background(), groupId).Accept(accept).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.ConfigureGroupDefaultHomeDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureGroupDefaultHomeDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **body** | **map[string]interface{}** | Request body for configuring the Default Home device experience. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureGroupInHouseLauncherDeviceExperience

> ConfigureGroupInHouseLauncherDeviceExperience(ctx, groupId).Accept(accept).ConfigureGroupInHouseLauncherDeviceExperienceRequest(configureGroupInHouseLauncherDeviceExperienceRequest).Execute()





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
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	configureGroupInHouseLauncherDeviceExperienceRequest := *openapiclient.NewConfigureGroupInHouseLauncherDeviceExperienceRequest(*openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner("Id_example", "Type_example"), []openapiclient.ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner("Id_example", "Type_example")}) // ConfigureGroupInHouseLauncherDeviceExperienceRequest | Request body for configuring the In-House Launcher device experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceExperienceAPI.ConfigureGroupInHouseLauncherDeviceExperience(context.Background(), groupId).Accept(accept).ConfigureGroupInHouseLauncherDeviceExperienceRequest(configureGroupInHouseLauncherDeviceExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.ConfigureGroupInHouseLauncherDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureGroupInHouseLauncherDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupInHouseLauncherDeviceExperienceRequest** | [**ConfigureGroupInHouseLauncherDeviceExperienceRequest**](ConfigureGroupInHouseLauncherDeviceExperienceRequest.md) | Request body for configuring the In-House Launcher device experience. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureGroupLockTaskDeviceExperience

> ConfigureGroupLockTaskDeviceExperience(ctx, groupId).Accept(accept).ConfigureGroupLockTaskDeviceExperienceRequest(configureGroupLockTaskDeviceExperienceRequest).Execute()





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
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	configureGroupLockTaskDeviceExperienceRequest := *openapiclient.NewConfigureGroupLockTaskDeviceExperienceRequest([]openapiclient.ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner("Id_example", "Type_example")}) // ConfigureGroupLockTaskDeviceExperienceRequest | Request body for configuring the Lock Task device experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceExperienceAPI.ConfigureGroupLockTaskDeviceExperience(context.Background(), groupId).Accept(accept).ConfigureGroupLockTaskDeviceExperienceRequest(configureGroupLockTaskDeviceExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.ConfigureGroupLockTaskDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureGroupLockTaskDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupLockTaskDeviceExperienceRequest** | [**ConfigureGroupLockTaskDeviceExperienceRequest**](ConfigureGroupLockTaskDeviceExperienceRequest.md) | Request body for configuring the Lock Task device experience. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceDeviceExperience

> GetGroupDeviceExperience200Response GetDeviceDeviceExperience(ctx, deviceId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceExperienceAPI.GetDeviceDeviceExperience(context.Background(), deviceId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.GetDeviceDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceDeviceExperience`: GetGroupDeviceExperience200Response
	fmt.Fprintf(os.Stdout, "Response from `DeviceExperienceAPI.GetDeviceDeviceExperience`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetGroupDeviceExperience200Response**](GetGroupDeviceExperience200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroupDeviceExperience

> GetGroupDeviceExperience200Response GetGroupDeviceExperience(ctx, groupId).Accept(accept).Execute()





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
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceExperienceAPI.GetGroupDeviceExperience(context.Background(), groupId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceExperienceAPI.GetGroupDeviceExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroupDeviceExperience`: GetGroupDeviceExperience200Response
	fmt.Fprintf(os.Stdout, "Response from `DeviceExperienceAPI.GetGroupDeviceExperience`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupDeviceExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetGroupDeviceExperience200Response**](GetGroupDeviceExperience200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

