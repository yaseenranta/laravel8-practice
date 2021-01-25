
## Laravel breeze Installation

- Configure Database first.
- Run `php artisan migrate` command.
- Install laravel breeeze using `composer require laravel/breeze --dev
` && `php artisan breeze:install` command.
- Install NPM Dependency `npm install` && `npm run dev`.
- Create admin user using seeder. Run following `php artisan make:seeder UserSeeder` && `php artisan db:seed --class=UserSeeder` command