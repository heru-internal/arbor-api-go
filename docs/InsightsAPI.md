# \InsightsAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**QueryInsightsData**](InsightsAPI.md#QueryInsightsData) | **Post** /insights/data/{insightsAppId} | 



## QueryInsightsData

> QueryInsightsData200Response QueryInsightsData(ctx, insightsAppId).Accept(accept).QueryInsightsDataRequest(queryInsightsDataRequest).Execute()





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
	insightsAppId := "123e4567-e89b-12d3-a456-426614174000" // string | The Insights App ID to query data for.
	queryInsightsDataRequest := *openapiclient.NewQueryInsightsDataRequest() // QueryInsightsDataRequest | Query insights analytics data (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InsightsAPI.QueryInsightsData(context.Background(), insightsAppId).Accept(accept).QueryInsightsDataRequest(queryInsightsDataRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InsightsAPI.QueryInsightsData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QueryInsightsData`: QueryInsightsData200Response
	fmt.Fprintf(os.Stdout, "Response from `InsightsAPI.QueryInsightsData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**insightsAppId** | **string** | The Insights App ID to query data for. | 

### Other Parameters

Other parameters are passed through a pointer to a apiQueryInsightsDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **queryInsightsDataRequest** | [**QueryInsightsDataRequest**](QueryInsightsDataRequest.md) | Query insights analytics data | 

### Return type

[**QueryInsightsData200Response**](QueryInsightsData200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

