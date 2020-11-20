# Swagger\Client\AnagraficaApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**anagraficaGet**](AnagraficaApi.md#anagraficaGet) | **GET** /v1/api/Anagrafica/Get | 
[**anagraficaInsertCliente**](AnagraficaApi.md#anagraficaInsertCliente) | **POST** /v1/api/Anagrafica/InsertCliente | 
[**anagraficaUpdateCliente**](AnagraficaApi.md#anagraficaUpdateCliente) | **POST** /v1/api/Anagrafica/UpdateCliente | 


# **anagraficaGet**
> \Swagger\Client\Model\Clienti anagraficaGet($cl_codice)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AnagraficaApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$cl_codice = "cl_codice_example"; // string | 

try {
    $result = $apiInstance->anagraficaGet($cl_codice);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AnagraficaApi->anagraficaGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cl_codice** | **string**|  |

### Return type

[**\Swagger\Client\Model\Clienti**](../Model/Clienti.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **anagraficaInsertCliente**
> \Swagger\Client\Model\Clienti[] anagraficaInsertCliente($raw_string, $controllo, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AnagraficaApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Clienti()); // \Swagger\Client\Model\Clienti[] | 
$controllo = true; // bool | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->anagraficaInsertCliente($raw_string, $controllo, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AnagraficaApi->anagraficaInsertCliente: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Clienti[]**](../Model/Clienti.md)|  |
 **controllo** | **bool**|  | [optional]
 **ambiente** | **string**|  | [optional]

### Return type

[**\Swagger\Client\Model\Clienti[]**](../Model/Clienti.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **anagraficaUpdateCliente**
> \Swagger\Client\Model\Clienti[] anagraficaUpdateCliente($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AnagraficaApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Clienti()); // \Swagger\Client\Model\Clienti[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->anagraficaUpdateCliente($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AnagraficaApi->anagraficaUpdateCliente: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Clienti[]**](../Model/Clienti.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

[**\Swagger\Client\Model\Clienti[]**](../Model/Clienti.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

