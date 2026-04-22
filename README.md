COMPONENTS

global:
- ToastNotification ✅
- LoadingSpinner ✅
- Button ✅

- forms (input, select etc.)✅
- tables✅
- Modal✅
- Image✅


Setting Up server (Laravel REST API)
- Creating server & installing packages ✅
    - composer create-project laravel/laravel project-name OR laravel new project-name (composer global require laravel/installer)
    - composer require laravel/sanctum
    - php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
    - composer require propaganistas/laravel-phone (https://github.com/Propaganistas/Laravel-Phone)
    - Setting up .env cors.php app.php
    - php artisan migrate (make sure to run your xampp first)

- Setting up migration, model, trait, resource, request, controller & api.php