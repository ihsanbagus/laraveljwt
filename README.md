<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## dependency

-   <a href="https://jwt-auth.readthedocs.io/en/develop/laravel-installation/">JWT Token / Tywon</a>

# installation

<b>Install via composer</b>
[code]composer require tymon/jwt-auth[/code]

<b>Publish the config</b>
[code]php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"[/code]

<b>Generate secret key</b>
[code]php artisan jwt:secret[/code]
This will update your .env file with something like JWT_SECRET=foobar

## author

<b><a href='https://www.ihsanbagus.com/'>Ihsan Bagus</a></b> 🐱‍🏍

## 2022
