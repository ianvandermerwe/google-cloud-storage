# google-cloud-storage

[![Packagist](https://img.shields.io/packagist/v/ianvdmerwe/google-cloud-storage.svg)]()
[![Software License][ico-license]](LICENSE.md)
[![Travis](https://img.shields.io/travis/ianvdmerwe/google-cloud-storage.svg)]()
[![Scrutinizer](https://img.shields.io/scrutinizer/g/ianvdmerwe/google-cloud-storage.svg)]()
[![Github All Releases](https://img.shields.io/github/downloads/ianvdmerwe/google-cloud-storage/total.svg)]()

This is a Package to upload files to the Google Cloud CDN.

## Install

``` bash
$ composer require ianvdmerwe/google-cloud-storage
```

## Add Service Provider

IoDigital\GoogleCloudStorage\GoogleCloudStorageServiceProvider::class

## Run Vendor publish

``` bash
$ php artisan vendor:publish

```

Configure the config file created

## Usage

``` php
$googleCloudHandler = new GoogleCloudStorageHandler();
$googleCloudHandler->uploadFile();

OR
use IoDigital\GoogleCloudStorage\Storage\GoogleCloudStorageHandler;
Dependency Inject: GoogleCloudStorageHandler
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email ian@io.co.za instead of using the issue tracker.

## Credits

- [Ian van der Merwe][https://github.com/ianvdmerwe]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/:vendor/:package_name.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/:vendor/:package_name/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/:vendor/:package_name.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/:vendor/:package_name.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/:vendor/:package_name.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/:vendor/:package_name
[link-travis]: https://travis-ci.org/:vendor/:package_name
[link-scrutinizer]: https://scrutinizer-ci.com/g/:vendor/:package_name/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/:vendor/:package_name
[link-downloads]: https://packagist.org/packages/:vendor/:package_name
[link-author]: https://github.com/:author_username
[link-contributors]: ../../contributors
