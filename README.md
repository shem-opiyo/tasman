# Tasman Backend
This is a Laravel backend application for the Tasman project.

## Technologies Used
- PHP 8.2+
- Laravel 12.0
- Composer for dependency management
## Installation
1. Clone the repository
2. Install PHP dependencies:
```
composer install
```
3. Install JavaScript dependencies:
```
npm install
```
4. Copy the .env.example file to .env:
```
cp .env.example .env
```
5. Generate the application key:
```
php artisan key:generate
```


Create the database file:
touch database/database.sqlite

bash


Run database migrations:
php artisan migrate

bash


Usage
To start the development server:

php artisan serve

bash


To run all development services (server, queue, logs, Vite) concurrently:

composer dev

bash


Project Structure
The project follows the standard Laravel structure:

app/ - Application logic and models
database/ - Database migrations and seeders
resources/ - Views and assets
routes/ - Web and API routes
tests/ - Unit and feature tests
Contributing
Contributions are welcome. Please follow the Laravel contribution guidelines.

License
This project is open-sourced software licensed under the MIT license.