Filipac Menus
=================
[![Laravel](https://img.shields.io/badge/Laravel-5.0-orange.svg?style=flat-square)](http://laravel.com)
[![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://tldrlegal.com/license/mit-license)

Based on [Caffeinated/menus](https://github.com/caffeinated/menus)

Easily create dynamic menus from within your Laravel 5 application.

Filipac Menus is originally based off of [Caffeinated/menus](https://github.com/caffeinated/menus) package; a fork to suit my needs. This has a primary focus on Laravel 5 support with PSR coding standards. If you're looking for a menu builder solution for Laravel 4, please go check out [Laravel Menu](https://github.com/lavary/laravel-menu)!

The package follows the FIG standards PSR-1, PSR-2, and PSR-4 to ensure a high level of interoperability between shared PHP code. At the moment the package is not unit tested, but is planned to be covered later down the road.

Quick Installation
------------------
Begin by installing the package through Composer. Add `Filipac/menus` to your composer.json file:

```
"filipac/menus": "~1.0@dev"
```

Then run `composer update` to pull the package in.

Once this operation is complete, simply add the service provider class and facade alias to your project's `config/app.php` file:

#### Service Provider
```php
'Filipac\Menus\MenusServiceProvider',
```

#### Facade
```
'Menu' => 'Filipac\Menus\Facades\Menu',
```

And that's it! With your coffee in reach, start building out some awesome menus!
