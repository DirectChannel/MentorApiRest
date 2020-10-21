# Swagger\Client\AttivitaApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**attivitaGet**](AttivitaApi.md#attivitaGet) | **GET** /v1/api/Attivita/Get | 
[**attivitaInsertAttivita**](AttivitaApi.md#attivitaInsertAttivita) | **POST** /v1/api/Attivita/InsertAttivita | 
[**attivitaUpdateAttivita**](AttivitaApi.md#attivitaUpdateAttivita) | **POST** /v1/api/Attivita/UpdateAttivita | 


# **attivitaGet**
> \Swagger\Client\Model\Attivita attivitaGet($id_attivita)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AttivitaApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$id_attivita = "id_attivita_example"; // string | 

try {
    $result = $apiInstance->attivitaGet($id_attivita);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AttivitaApi->attivitaGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id_attivita** | **string**|  |

### Return type

[**\Swagger\Client\Model\Attivita**](../Model/Attivita.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **attivitaInsertAttivita**
> \Swagger\Client\Model\Attivita[] attivitaInsertAttivita($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AttivitaApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Attivita()); // \Swagger\Client\Model\Attivita[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->attivitaInsertAttivita($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AttivitaApi->attivitaInsertAttivita: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Attivita[]**](../Model/Attivita.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

[**\Swagger\Client\Model\Attivita[]**](../Model/Attivita.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **attivitaUpdateAttivita**
> \Swagger\Client\Model\Attivita[] attivitaUpdateAttivita($raw_string, $ambiente)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AttivitaApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Attivita()); // \Swagger\Client\Model\Attivita[] | 
$ambiente = "ambiente_example"; // string | 

try {
    $result = $apiInstance->attivitaUpdateAttivita($raw_string, $ambiente);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AttivitaApi->attivitaUpdateAttivita: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Attivita[]**](../Model/Attivita.md)|  |
 **ambiente** | **string**|  | [optional]

### Return type

[**\Swagger\Client\Model\Attivita[]**](../Model/Attivita.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

