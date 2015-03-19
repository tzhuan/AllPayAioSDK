# Allpay/all-in-one

Composer package for [allpay](https://www.allpay.com.tw)'s SDK


## Installation

Add the following lines to your `composer.json` and run `composer install`.

```json
"repositories": [
    {  
        "type": "vcs",
        "url": "https://github.com/tzhuan/AllPayAioSDK"
    }
],
"require": {
    "allpay/all-in-one": "1.0.*"
}
```

## Usage

```php
require 'vendor/autoload.php';
$aio = new AllInOne();
```

See `歐付寶全方位金流SDK技術文件.pdf` for more information.
