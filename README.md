<h2 align="center">Laravel Lang C.M.S.</h2>
<h3 align="center">~ A content management system for Laravel project language files.</h3>
<br><br>
<p align="center"><img src="https://raw.githubusercontent.com/raysirsharp/img-storage/master/lang-cms-header.png"></p>
<p align="center">
<a target="_blank" href="https://laravel.com/"><img src="https://img.shields.io/badge/Built%20For-Laravel-orange" alt="Built For Laravel"></a>
<a target="_blank" href="https://packagist.org/packages/raysirsharp/laravel-lang-cms"><img src="https://img.shields.io/badge/Current%20Version-0.1.1-blue" alt="Version"></a>
<a target="_blank" href="https://packagist.org/packages/raysirsharp/laravel-lang-cms"><img src="https://img.shields.io/badge/License-MIT-green" alt="License"></a>
<a target="_blank" href="https://laravel.com/"><img src="https://img.shields.io/badge/Requires-Laravel%20%5E7.0-red" alt="Requires"></a>
</p>

## What is Laravel Lang CMS

TODO

## Installation
- `composer require raysirsharp/laravel-lang-cms`
- `php artisan vendor:publish --tag=public --force`
- Access from http(s)://your-project-url.com/lang-cms

## Usage

#### Enable/Disable
- `php artisan lang-cms:toggle {--off} {--on}`

#### Edit/No Edit
Activate / Diable "view only" mode 
- `php artisan lang-cms:edit {--off} {--on}`

#### Change access password
The default access password is "lang-cms-admin", to change it (reccomended) use:
- `php artisan lang-cms:set password`

#### Change support email
The default support email address is NULL. The support message in this case states to contact the system admin for help logging in. If you wish to specify a support email address instead use:
- `php artisan lang-cms:set support_email`

## Licence
Laravel Lang CMS is open-sourced software licensed under the [MIT license](LICENSE.md).
