# Laravel Template (AdminLTE UI v3)

This is only a Laravel Template using the AdminLTE UI v3

**Visit the adminlte template [here](https://adminlte.io/themes/v3)**

## Features
* Basic Authentication (with default user)

## Component's Version
* Laravel 8
* AdminLTE v3

## Installation
1. git clone https://github.com/ageesea/laravel-template-adminlte-3.git
2. `cd laravel-template-adminlte-3`
3. Remove `.git` folder

> Since this is a template, you need to remove the .git folder so that you can initialize your own repository.

4. `composer install` - to install dependencies
5. `cp .env.example .env` - to copy the default environment file to a new file
6. `php artisan key:generate` - generate laravel application key
7. `php artisan migrate --seed` - to migrate database and load default data

> Note! you need to edit your .env file with your credentials before executing the above command.

8. `npm install` - to install javascript dependencies.
9. `npm run dev` - to compile javascript files in development mode.
   
> You can run `npm run prod` to compile javascript files in production mode

> You can also run `npm run watch` to watch your javascript files and compile when there's a change.

10. Done! You can now modify the template according to your project specifications.

## How to use
* This project uses the laravel's legacy authentication using Laravel/UI 

## Licenses
1. The license of the AdminLTE v3 can be found [here](https://adminlte.io/docs/3.0/license.html).

## Issues
