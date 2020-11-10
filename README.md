<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel Breeze Demo

This is a simple repo demonstrating the usage of [Laravel Breeze](https://github.com/laravel/breeze). 

## Installation Steps for Laravel Breeze

```php
laravel new my-app

cd my-app

composer require laravel/breeze --dev

php artisan breeze:install

```

Then you have to run:

```php
npm install && npm run dev
```

Run migrations:

```php
php artisan migrate
```

If you run the app, you will see `Login` and `Register` options in the homepage, and once registered and logged in, you will be greeted in the dashboard.


