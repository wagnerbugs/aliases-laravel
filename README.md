<h1 align="center">Laravel Bash Aliases</h1>

<p align="center">
<a href="https://github.com/sindresorhus/awesome">
    <img align="center" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
</a>
    
🚀 My list of useful aliases for development in Laravel projects.

## Contents

- [Contents](#contents)
      - [Artisan](#artisan)
      - [Packages](#packages)
      - [Composer](#composer)
      - [Database](#database)
      - [Others](#others)

<a id="artisan"></a>
#### Artisan Console
##### [ARTISAN](https://laravel.com/docs/artisan)
    alias pa='php artisan'
    alias serve='pa serve'
    alias controller='pa make:controller'
    alias migration='pa make:migration'
    alias model='pa make:model'
    alias migrate='pa migrate'
    alias route='pa route:list'
    alias key="pa key:generate"
    alias clean='pa config:clear && pa cache:clear && pa view:clear && pa route:clear'

<a id="packages"></a>
#### Packages Laravel
##### [TINKER](https://laravel.com/docs/artisan#tinker)
    alias tinker='pa tinker'
    
##### [BREEZE](https://laravel.com/docs/starter-kits#laravel-breeze)
    alias breeze='composer require laravel/breeze --dev && pa breeze:install && pa migrate && npm install'
    
##### [DEBUGBAR](https://github.com/barryvdh/laravel-debugbar)
    alias debugbar='composer require barryvdh/laravel-debugbar --dev'
    
##### [PINT](https://laravel.com/docs/pint)
    alias pinti='composer require laravel/pint --dev'
    alias pintj='echo -e { \"preset\":\"laravel\" } >> pint.json'
    alias pint='./vendor/bin/pint'

    
<a id="composer"></a>
#### Composer
##### [COMPOSER](https://getcomposer.org/)
    alias ci='composer install'
    alias cu='composer update'
    alias dump='composer dump-autoload'
    alias dumpo='composer dump-autoload -o'

<a id="database"></a>
#### Database Mysql
##### [CONNECTION](https://www.cobgiro.com/arquivos/mysql2.pdf)
    alias my='mysql -u root -p'

<a id="others"></a>
#### Others
    alias brc='code ~/.bashrc'
    alias refresh='exec bash'
    alias cls='clear'
