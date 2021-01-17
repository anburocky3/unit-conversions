# Simple unit converter

[![Latest Version on Packagist](https://img.shields.io/packagist/v/anburocky3/unit-conversions.svg?style=flat-square)](https://packagist.org/packages/anburocky3/unit-conversions)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/anburocky3/unit-conversions/Tests?label=tests)](https://github.com/anburocky3/unit-conversions/actions?query=workflow%3ATests+branch%3Amaster)
[![Total Downloads](https://img.shields.io/packagist/dt/anburocky3/unit-conversions.svg?style=flat-square)](https://packagist.org/packages/anburocky3/unit-conversions)


This is very simple php package where you can use to convert the values to your preferred units.

## Installation

You can install the package via composer:

```bash
composer require anburocky3/unit-conversions
```

## Usage

```php
$lbs = Weight::fromKilograms(100)->toLbs();
echo $lbs;
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

- [Anbu](https://github.com/anburocky3)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
