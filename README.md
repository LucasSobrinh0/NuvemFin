# NuvemFin

To create this project, we used the following configuration:

- Command: `laravel new NuvemFin`
- Frontend preset: None
- Testing framework: Pest
- Database: SQLite
- Build step: `npm install` and `npm run build` (yes)

To make migrations

php artisan migrate

Run the server

php artisan serve

php artisan make:migration create_categories_table
php artisan make:model Category
php artisan make:controller CategoryController --resource
php artisan make:model Category -mcr

php artisan route:list

php artisan optimize:clear && php artisan migrate


npm run dev

php artisan serve


composer require laravel/breeze --dev
php artisan breeze:install blade
