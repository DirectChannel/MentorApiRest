# Swagger\Client\VersamentoApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**versamentoGet**](VersamentoApi.md#versamentoGet) | **GET** /v1/api/Versamento/Get | 
[**versamentoInsertVersamento**](VersamentoApi.md#versamentoInsertVersamento) | **POST** /v1/api/Versamento/InsertVersamento | 
[**versamentoUpdateAttivita**](VersamentoApi.md#versamentoUpdateAttivita) | **POST** /v1/api/Versamento/UpdateAttivita | 


# **versamentoGet**
> \Swagger\Client\Model\Versamento[] versamentoGet($codice_cliente, $data_inizio, $data_fine, $id_regolare)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VersamentoApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$codice_cliente = "codice_cliente_example"; // string | 
$data_inizio = "data_inizio_example"; // string | 
$data_fine = "data_fine_example"; // string | 
$id_regolare = "id_regolare_example"; // string | 

try {
    $result = $apiInstance->versamentoGet($codice_cliente, $data_inizio, $data_fine, $id_regolare);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling VersamentoApi->versamentoGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **codice_cliente** | **string**|  |
 **data_inizio** | **string**|  | [optional]
 **data_fine** | **string**|  | [optional]
 **id_regolare** | **string**|  | [optional]

### Return type

[**\Swagger\Client\Model\Versamento[]**](../Model/Versamento.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **versamentoInsertVersamento**
> \Swagger\Client\Model\Versamento[] versamentoInsertVersamento($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VersamentoApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Versamento()); // \Swagger\Client\Model\Versamento[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->versamentoInsertVersamento($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling VersamentoApi->versamentoInsertVersamento: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Versamento[]**](../Model/Versamento.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

[**\Swagger\Client\Model\Versamento[]**](../Model/Versamento.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **versamentoUpdateAttivita**
> \Swagger\Client\Model\Versamento[] versamentoUpdateAttivita($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VersamentoApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Versamento()); // \Swagger\Client\Model\Versamento[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->versamentoUpdateAttivita($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling VersamentoApi->versamentoUpdateAttivita: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Versamento[]**](../Model/Versamento.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

[**\Swagger\Client\Model\Versamento[]**](../Model/Versamento.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

