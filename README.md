# Flipmart eCommerce system

## About Repository

Flipmart is a complete ecommerce system based on Laravel 8.
Frontend system provide a complete online interface to order products from online.
Backend system provide a complete management of the ecommerce system.

## Tech Specification

- Laravel 8
- jQuery 3
- Bootstrap 4
- Font Awesome 5
- Intervention Image
- alertify js

## Features

- Complete ecommerce system
- Login, Register, using default Jetstream auth
- Show, update, edit, and delete products as admin
- Show, update, edit, and delete category as admin
- Show, update, edit, and delete brands as admin
- Search Products
- product checkout
- local payment system
- user dashboard
- Authorization

## Installation

- `git clone https://github.com/SBTHDR/flipmart.git`
- `cd flipmart/`
- `cp .env.example .env`
- `composer install`
- Run `php artisan key:generate`
- Update `.env` and set your database credentials
- `php artisan migrate`
- `npm install`
- `npm run dev`
- `php artisan serve`

## License

[MIT license](https://opensource.org/licenses/MIT).