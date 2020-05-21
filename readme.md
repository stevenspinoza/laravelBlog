# Laravel Blog

A simple blog based on Laravel 7.0

## Requirements

- Laravel 7.0
- PHP >= 7.0

## Login

user: admin@admin.com 
password: admin


## Installation Steps

```
git clone
cd laravelBlog
composer install
cp .env.example .env
update vars in .env
php artisan key:generate
php artisan migrate
php artisan db:seed

php artisan serve for running server on localhost:8000

```

