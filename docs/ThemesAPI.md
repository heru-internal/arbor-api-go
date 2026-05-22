# \ThemesAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTheme**](ThemesAPI.md#CreateTheme) | **Post** /themes | 
[**DeleteTheme**](ThemesAPI.md#DeleteTheme) | **Delete** /themes/{themeId} | 
[**GetTheme**](ThemesAPI.md#GetTheme) | **Get** /themes/{themeId} | 
[**GetThemes**](ThemesAPI.md#GetThemes) | **Get** /themes | 
[**UpdateTheme**](ThemesAPI.md#UpdateTheme) | **Put** /themes/{themeId} | 



## CreateTheme

> GetThemes200ResponseDataInner CreateTheme(ctx).Accept(accept).CreateThemeRequest(createThemeRequest).Execute()





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
	createThemeRequest := *openapiclient.NewCreateThemeRequest("Dark Theme", "#1a1a1a", "#2a2a2a", "#ffffff", "#007bff", "#28a745", "#dc3545") // CreateThemeRequest | Create a new theme. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ThemesAPI.CreateTheme(context.Background()).Accept(accept).CreateThemeRequest(createThemeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ThemesAPI.CreateTheme``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTheme`: GetThemes200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `ThemesAPI.CreateTheme`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateThemeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **createThemeRequest** | [**CreateThemeRequest**](CreateThemeRequest.md) | Create a new theme. | 

### Return type

[**GetThemes200ResponseDataInner**](GetThemes200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteTheme

> DeleteTheme(ctx, themeId).Accept(accept).Execute()





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
	themeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the theme.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ThemesAPI.DeleteTheme(context.Background(), themeId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ThemesAPI.DeleteTheme``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**themeId** | **string** | The ID of the theme. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteThemeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTheme

> GetThemes200ResponseDataInner GetTheme(ctx, themeId).Accept(accept).Execute()





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
	themeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the theme.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ThemesAPI.GetTheme(context.Background(), themeId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ThemesAPI.GetTheme``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTheme`: GetThemes200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `ThemesAPI.GetTheme`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**themeId** | **string** | The ID of the theme. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetThemeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetThemes200ResponseDataInner**](GetThemes200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetThemes

> GetThemes200Response GetThemes(ctx).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	resp, r, err := apiClient.ThemesAPI.GetThemes(context.Background()).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ThemesAPI.GetThemes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetThemes`: GetThemes200Response
	fmt.Fprintf(os.Stdout, "Response from `ThemesAPI.GetThemes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetThemesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetThemes200Response**](GetThemes200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTheme

> GetThemes200ResponseDataInner UpdateTheme(ctx, themeId).Accept(accept).CreateThemeRequest(createThemeRequest).Execute()





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
	themeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the theme.
	createThemeRequest := *openapiclient.NewCreateThemeRequest("Dark Theme", "#1a1a1a", "#2a2a2a", "#ffffff", "#007bff", "#28a745", "#dc3545") // CreateThemeRequest | Update a theme. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ThemesAPI.UpdateTheme(context.Background(), themeId).Accept(accept).CreateThemeRequest(createThemeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ThemesAPI.UpdateTheme``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTheme`: GetThemes200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `ThemesAPI.UpdateTheme`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**themeId** | **string** | The ID of the theme. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateThemeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **createThemeRequest** | [**CreateThemeRequest**](CreateThemeRequest.md) | Update a theme. | 

### Return type

[**GetThemes200ResponseDataInner**](GetThemes200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

