# PHP Code Sniffing for WordPress

## Requirements

Composer

## Install

```bash
composer require ngearing/phpcs-wp:dev-master
```

## How to use

From the root of your project directory run the following from your terminal:

```bash
vendor/bin/phpcs .
```

Or to fix errors

```bash
vendor/bin/phpcbf .
```

To check PHP compatibilty

```bash
vendor/bin/phpcs --runtime-set testVersion 7.0-
```
