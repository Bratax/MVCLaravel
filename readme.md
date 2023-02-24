



### Prerequisites
What things you need to install the software.

* Git.
* PHP.
* Composer.
* Laravel CLI.
* Laravel Valet (optional).
* A webserver like Nginx or Apache.

### Install
Clone the git repository on your computer
```
$ git clone https://github.com/neoighodaro-articles/laravel-mvc-demo.git
```

You can also download the entire repository as a zip file and unpack in on your computer if you do not have git

After cloning the application, you need to install it's dependencies. 
```
$ cd laravel-mvc
$ composer install
```

### Setup
When you are done with installation, copy the `.env.example` file to `.env`
```
$ cp .env.example .env
```

Generate the application key
```
$ php artisan key:generate
```

Add your database credentials to the necessary `env` fields

Migrate the application
```
$ php artisan migrate
```

### Run the application
```
$ php artisan serve
```

## Built With
* [Laravel](https://laravel.com) - The PHP framework for building the API endpoints needed for the application

## Acknowledgments
* [Laravel](https://laravel.com) - The excellent documentation explaining how to get started with Laravel and Laravel Passport made it easy to provide a step by step guide for beginners to follow the application.
