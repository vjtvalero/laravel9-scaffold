<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel 9 Scaffold

This scaffold uses the default [Breeze & Blade](https://laravel.com/docs/9.x/starter-kits#breeze-and-blade) stack from the Laravel Breeze documentation.

## Requirements

Your machine must be running at least PHP version 8.

Get the latest version at [https://windows.php.net/download](https://windows.php.net/download)

## Quickstart

After cloning this repo, run:

```sh
composer install
```
 
<br />

Create your .env file by copying the contents from .env.example.

Edit your .env file to match your DB configuration. Then run:

```sh
php artisan migrate

# Generates app key
php artisan key:generate
```

<br />

Install the Breeze package:

```sh
npm install

# Compiles the frontend assets
npm run dev
```

<br />

Open a new terminal then run:

```sh
php artisan serve
```


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
