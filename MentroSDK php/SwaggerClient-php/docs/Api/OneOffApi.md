# Swagger\Client\OneOffApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**oneOffGet**](OneOffApi.md#oneOffGet) | **GET** /v1/api/OneOff/Get | 


# **oneOffGet**
> object oneOffGet($id_oneoff)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\OneOffApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$id_oneoff = "id_oneoff_example"; // string | 

try {
    $result = $apiInstance->oneOffGet($id_oneoff);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling OneOffApi->oneOffGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id_oneoff** | **string**|  |

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

