# BitlyApi [![Build Status](https://travis-ci.org/hpatoio/bitly-api.png?branch=master)](https://travis-ci.org/hpatoio/bitly-api) [![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/hpatoio/bitly-api/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

PHP Library based on Guzzle to consume Bit.ly API

Installation
============

The recommended way to install this bundle is through composer:

```json
{
    "require": {
        "hpatoio/bitly-api": "dev-master"
    }
}
```

## Usage

```php
<?php

// This file is generated by Composer
require_once 'vendor/autoload.php';

# To find your bitly access token see here https://bitly.com/a/oauth_apps
$my_bitly = new \Bitly\Api\BitlyClient("insert_here_your_bitly_api_key");

$response = $my_bitly->Highvalue(array("limit" => 3));

print_r($response);

```


