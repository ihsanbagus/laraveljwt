<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## dependency

-   <a href="https://jwt-auth.readthedocs.io/en/develop/laravel-installation/">JWT Token / Tywon</a>

# installation

<b>Install via composer</b>

```sh
composer require tymon/jwt-auth
```

<b>Publish the config</b>

```sh
php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"
```

<b>Generate secret key</b>

```sh
php artisan jwt:secret
```

This will update your .env file with something like JWT_SECRET=foobar

## author

<b><a href='https://www.ihsanbagus.com/'>Ihsan Bagus</a></b> 🐱‍🏍

## method

```
POST https://localhost:8000/api/auth/login
POST https://localhost:8000/api/auth/logout
POST https://localhost:8000/api/auth/refresh
POST https://localhost:8000/api/auth/me
```
