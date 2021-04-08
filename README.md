<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License">
</p>

## About Money Expense Manager
Money Expense Manager application is a web application framework with expressive, elegant syntax and build with laravel 5.4.32 . This is open source project under MIT License. That means its free and you can contribute to this open source project.

## Working Method:
This application fully custom made and used many open source Jquery file. and all other custom made.



Project Framework
- Laravel 5.4.32
-  PHP

## Server Requirements

This Covid19 project has a few system requirements. You should ensure that your web server has the following minimum PHP version and extensions:
-   PHP >= 5.6.4
-   OpenSSL PHP Extension
-   PDO PHP Extension
-   Mbstring PHP Extension
-   Tokenizer PHP Extension
-   XML PHP Extension
- fopen_url_allow = true
- composer

## How to install
**clone this project**
```
https://github.com/mahbuburriad/expensemanager.git
```
> Go to Directory `core`

**Open Terminal and install the composer**
```
composer install
```
**make an .env file**
```
cp .env.example .env
```
**Open .env file and modify the database name, username and password**
```
DB_CONNECTION=mysql  
DB_HOST=localhost  
DB_PORT=3306  
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```
**generate Key**
```
php artisan key:generate
```
**Storage Link**
```
php artisan storage:link
```

## Database Upload
Go to `Database File` folder > Here you will find expense.sql file. Import this database file to your desire database.

## Login Information
> Admin : admin@example.com
> Password: 123456

## Contact Information
For any type of problem comment here or knock me on mail
Mail: mahbubur.riad@gmail.com
website: https://mahbuburriad.com

## Contributing

Thank you for considering contributing to the Expense Manager Project. You can contribute this project whatever need and update.

## Code of Conduct

In order to ensure that the Expense Manager project member is welcoming to all

## Security Vulnerabilities

If you discover a security vulnerability within Expense Manager project, please send an e-mail to Mahbubur Riad via [mahbubur.riad@gmail.com](mailto:mahbubur.riad@gmail.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).