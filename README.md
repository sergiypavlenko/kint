# Laravel 3 Bundle Kint - debugging helper for PHP developers

## What?

Kint for PHP is a powerful and modern, zero-setup replacement for var_dump(), print_r() and debug_backtrace(). You'll wonder how you developed without it.

Read more - [https://github.com/raveren/kint/](https://github.com/raveren/kint/)

## Installation

Add to file application/bundles.php:

```php
'kint' => array('auto' => true)
```

OR

You can install bundle by running the following CLI command:

```
php artisan bundle:install kint
```

## Usage

You can use all the functions with the primary functional.