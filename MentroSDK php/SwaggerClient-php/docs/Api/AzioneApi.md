# Swagger\Client\AzioneApi

All URIs are relative to *https://dc.directchannel.it/ApiRest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**azioneInsertAzione**](AzioneApi.md#azioneInsertAzione) | **POST** /v1/api/Azione/InsertAzione | 


# **azioneInsertAzione**
> \Swagger\Client\Model\Azione[] azioneInsertAzione($raw_string)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AzioneApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$raw_string = array(new \Swagger\Client\Model\Azione()); // \Swagger\Client\Model\Azione[] | 

try {
    $result = $apiInstance->azioneInsertAzione($raw_string);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AzioneApi->azioneInsertAzione: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **raw_string** | [**\Swagger\Client\Model\Azione[]**](../Model/Azione.md)|  |

### Return type

[**\Swagger\Client\Model\Azione[]**](../Model/Azione.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

