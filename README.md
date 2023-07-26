# This is my package filament-simple-color-picker

[![Latest Version on Packagist](https://img.shields.io/packagist/v/rockero-cz/filament-simple-color-picker.svg?style=flat-square)](https://packagist.org/packages/rockero-cz/filament-simple-color-picker)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/rockero-cz/filament-simple-color-picker/run-tests?label=tests)](https://github.com/rockero-cz/filament-simple-color-picker/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/rockero-cz/filament-simple-color-picker/Check%20&%20fix%20styling?label=code%20style)](https://github.com/rockero-cz/filament-simple-color-picker/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/rockero-cz/filament-simple-color-picker.svg?style=flat-square)](https://packagist.org/packages/rockero-cz/filament-simple-color-picker)



This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Installation

You can install the package via composer:

```bash
composer require rockero-cz/filament-simple-color-picker
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="filament-simple-color-picker-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="filament-simple-color-picker-config"
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="filament-simple-color-picker-views"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

```php
$filament-simple-color-picker = new Rockero\FilamentSimpleColorPicker();
echo $filament-simple-color-picker->echoPhrase('Hello, Rockero!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Rockero-cz](https://github.com/rockero-cz)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
