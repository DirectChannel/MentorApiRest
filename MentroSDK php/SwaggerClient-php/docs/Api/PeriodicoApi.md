# Swagger\Client\PeriodicoApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**periodicoCallPeriodico**](PeriodicoApi.md#periodicoCallPeriodico) | **POST** /v1/api/Periodico/CallPeriodico | 
[**periodicoGet**](PeriodicoApi.md#periodicoGet) | **GET** /v1/api/Periodico/Get | 
[**periodicoInsertPeriodici**](PeriodicoApi.md#periodicoInsertPeriodici) | **POST** /v1/api/Periodico/InsertPeriodici | 
[**periodicoUpdateAttivita**](PeriodicoApi.md#periodicoUpdateAttivita) | **POST** /v1/api/Periodico/UpdateAttivita | 


# **periodicoCallPeriodico**
> object periodicoCallPeriodico($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\PeriodicoApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = new \Swagger\Client\Model\CallRegolare(); // \Swagger\Client\Model\CallRegolare | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->periodicoCallPeriodico($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PeriodicoApi->periodicoCallPeriodico: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\CallRegolare**](../Model/CallRegolare.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **periodicoGet**
> object periodicoGet($cl_codice)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\PeriodicoApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$cl_codice = "cl_codice_example"; // string | 

try {
    $result = $apiInstance->periodicoGet($cl_codice);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PeriodicoApi->periodicoGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cl_codice** | **string**|  |

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **periodicoInsertPeriodici**
> object periodicoInsertPeriodici($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\PeriodicoApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Periodici()); // \Swagger\Client\Model\Periodici[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->periodicoInsertPeriodici($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PeriodicoApi->periodicoInsertPeriodici: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Periodici[]**](../Model/Periodici.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **periodicoUpdateAttivita**
> object periodicoUpdateAttivita($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\PeriodicoApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Periodici()); // \Swagger\Client\Model\Periodici[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->periodicoUpdateAttivita($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PeriodicoApi->periodicoUpdateAttivita: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Periodici[]**](../Model/Periodici.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

