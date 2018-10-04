# Laravel preset artisan command for Lumen

Swap the front-end scaffolding for the application

> **Note:** This repository contains the code taken from Laravel 5.7.

**Installation**

Require the package from your `composer.json` file


```php
"require": {
    "toxageek/lumen-preset": "*"
}
```

and run `$ composer update` or both in one with `$ composer require toxageek/lumen-preset`.


Next register the following Console Command to your `app/Console/Kernel.php` file

```php
protected $commands = [
    
];
```

## Usage

Call `php artisan preset -h` in console.

## License

This package is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).