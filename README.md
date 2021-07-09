Best2Pay integration
====================
Best2Pay API integration (including Symfony service provider)



## Installation
```bash
composer require pvs812/best2pay
```

### Symfony service registration
Package supports auto discovery for Symfony >= 5.2

You can also add Facade (`configs/app.php`)
```php
'aliases' => [
    ...
    'Best2Pay' => Kozz\Best2Pay\Laravel\Facades\Best2PayFacade::class
],
```

Then run command (it will create `config/best2pay.php` file)

```bash
php artisan vendor:publish
```

