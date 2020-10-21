# Swagger\Client\TokenApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**tokenAutenticationGet**](TokenApi.md#tokenAutenticationGet) | **GET** /v1/api/Token/autentication | 
[**tokenGet**](TokenApi.md#tokenGet) | **GET** /v1/api/Token | 
[**tokenVerifiToken**](TokenApi.md#tokenVerifiToken) | **GET** /v1/api/Token/verify | 


# **tokenAutenticationGet**
> string tokenAutenticationGet($utente, $chiave, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TokenApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$utente = "utente_example"; // string | 
$chiave = "chiave_example"; // string | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->tokenAutenticationGet($utente, $chiave, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TokenApi->tokenAutenticationGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **utente** | **string**|  |
 **chiave** | **string**|  |
 **ambiente** | **string**|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **tokenGet**
> object tokenGet()



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TokenApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->tokenGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TokenApi->tokenGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **tokenVerifiToken**
> object tokenVerifiToken()



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TokenApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->tokenVerifiToken();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TokenApi->tokenVerifiToken: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

