# Swagger\Client\AdozioniApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**adozioniGet**](AdozioniApi.md#adozioniGet) | **GET** /v1/api/Adozioni/Get | 
[**adozioniInsertAdozioni**](AdozioniApi.md#adozioniInsertAdozioni) | **POST** /v1/api/Adozioni/InsertAdozioni | 
[**adozioniUpdateAdozioni**](AdozioniApi.md#adozioniUpdateAdozioni) | **POST** /v1/api/Adozioni/UpdateAdozioni | 


# **adozioniGet**
> object adozioniGet($codice_adozione)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AdozioniApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$codice_adozione = "codice_adozione_example"; // string | 

try {
    $result = $apiInstance->adozioniGet($codice_adozione);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AdozioniApi->adozioniGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **codice_adozione** | **string**|  |

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **adozioniInsertAdozioni**
> object adozioniInsertAdozioni($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AdozioniApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Adozioni()); // \Swagger\Client\Model\Adozioni[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->adozioniInsertAdozioni($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AdozioniApi->adozioniInsertAdozioni: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Adozioni[]**](../Model/Adozioni.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **adozioniUpdateAdozioni**
> object adozioniUpdateAdozioni($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AdozioniApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Adozioni()); // \Swagger\Client\Model\Adozioni[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->adozioniUpdateAdozioni($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AdozioniApi->adozioniUpdateAdozioni: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Adozioni[]**](../Model/Adozioni.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

