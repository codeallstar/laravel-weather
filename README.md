# Laravel Weather

[![Latest Stable Version](https://poser.pugx.org/torann/laravel-weather/v/stable.png)](https://packagist.org/packages/torann/laravel-weather) [![Total Downloads](https://poser.pugx.org/torann/laravel-weather/downloads.png)](https://packagist.org/packages/torann/laravel-weather)

Just a simple weather package for Laravel.

----------

## Installation

- [Laravel Repository on Packagist](https://packagist.org/packages/torann/laravel-repository)
- [Laravel Repository on GitHub](https://github.com/torann/laravel-repository)

To get the latest version of Laravel Weather simply require it in your `composer.json` file.

~~~
"torann/laravel-weather": "0.1.*@dev"
~~~

You'll then need to run `composer install` to download it and have the autoloader updated.

### Publish package assets:

```
$ php artisan asset:publish torann/laravel-weather
```

Add the following to the page where the Laravel Weather widget script will be active:

```
{{ HTML::style('/packages/torann/laravel-weather/weather.css') }} 
```

If using [Duct](https://github.com/torann/asset-duct) add this to the CSS manifest file:

```
 *= require torann/laravel-weather/weather.css
```

## Documentation

[View the official documentation](https://github.com/Torann/laravel-weather/wiki).