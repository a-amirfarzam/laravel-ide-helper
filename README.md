# IDE Helper Generator for Laravel


## In Composer

```bash
composer require --dev barryvdh/laravel-ide-helper
```




- add the package to the `extra.laravel.dont-discover` key in `composer.json`, e.g.
  ```json
  "extra": {
    "laravel": {
      "dont-discover": [
        "barryvdh/laravel-ide-helper"
      ]
    }
  }
  ```
- Add the following class to the `providers` array in `config/app.php`:
  ```php
  Barryvdh\LaravelIdeHelper\IdeHelperServiceProvider::class,
  ```
 
## In PHP

```php
php artisan ide-helper:generate
php artisan ide-helper:models
php artisan ide-helper:meta
```
