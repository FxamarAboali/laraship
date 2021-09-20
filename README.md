# Giga Store

This project runs with Laravel version 7.4

## Getting started

Assuming you've already installed on your machine: PHP (>= 7.0.0), [Laravel](https://laravel.com) and [Composer](https://getcomposer.org).
``` bash
# install dependencies
composer install

# create .env file and generate the application key
cp .env.example .env
php artisan key:generate
php artisan migrate:fresh --seed
php artisan passport:install

``` bash
php artisan serve
```

## Default Login
Admin
user: superuser@dav.io / password: admin123

User
user: member@dav.io / password: member123

The Giga store project is now up and running! Access it at http://localhost:8000.

For More Laraship guidelines you can check their websites for installation guids and documentation

``
installation guide
``
https://www.laraship.com/docs/laraship/welcome-to-laraship/

``
Laraship api documentation
``
https://www.laraship.com/api/

