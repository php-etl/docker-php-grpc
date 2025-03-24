# Docker container with PHP based on alpine image

These images are based on Spiral Scout's images you can find here: https://github.com/spiral/docker-php-grpc

The ZTS images were not provided by the former repository. ZTS is required when using [FrankenPHP](https://frankenphp.dev/),
especially when you use modern versions of [API Platform](https://api-platform.com/) 

Enabled extensions
===

| Extension | PHP 8.1 | PHP 8.2 | PHP 8.3 | PHP 8.4 |
|-----------|---------|---------|---------|---------|
| opcache   | ✅       | ✅       | ✅       | ✅       |
| zip       | ✅       | ✅       | ✅       | ✅       |
| xsl       | ✅       | ✅       | ✅       | ✅       |
| dom       | ✅       | ✅       | ✅       | ✅       |
| exif      | ✅       | ✅       | ✅       | ✅       |
| intl      | ✅       | ✅       | ✅       | ✅       |
| pcntl     | ✅       | ✅       | ✅       | ✅       |
| bcmath    | ✅       | ✅       | ✅       | ✅       |
| sockets   | ✅       | ✅       | ✅       | ✅       |
| protobuf  | ✅       | ✅       | ✅       | ✅       |
| grpc      | ✅       | ✅       | ✅       | ✅       |

Available images
===

### PHP 8.4 images

* No ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.4-cli`
* With ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.4-zts`
* No ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.4-cli-xdebug`
* With ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.4-zts-xdebug`

### PHP 8.3 images

* No ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.3-cli`
* With ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.3-zts`
* No ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.3-cli-xdebug`
* With ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.3-zts-xdebug`

### PHP 8.2 images

* No ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.2-cli`
* With ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.2-zts`
* No ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.2-cli-xdebug`
* With ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.2-zts-xdebug`

### PHP 8.1 images

* No ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.1-cli`
* With ZTS, no Xdebug: `ghcr.io/php-etl/php-grpc:8.1-zts`
* No ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.1-cli-xdebug`
* With ZTS, with Xdebug: `ghcr.io/php-etl/php-grpc:8.1-zts-xdebug`
