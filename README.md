# Laravel Breeze CRUD App

Laravel Breeze CRUD App is a web application built with Laravel and Laravel Breeze, focused on implementing CRUD operations using Laravel’s conventional MVC structure.

The project includes Laravel’s standard backend structure, Blade-based views, database configuration, frontend tooling with Vite and Tailwind CSS, and the default Laravel testing structure.

> The finalized version of this project is maintained in the `v4` branch.

---

## Overview

This project was developed as a Laravel web application using Laravel Breeze as the foundation for the application structure.

The repository demonstrates a CRUD-oriented Laravel project with organized backend directories, Blade views, database-related files, routing structure, and frontend build configuration.

The main goal of this project is to practice and demonstrate Laravel fundamentals, including routing, MVC organization, database-backed operations, Blade templates, and frontend asset management.

---

## Features

- Laravel-based web application structure
- CRUD-oriented project implementation
- Blade template structure
- Laravel routing organization
- Database-ready project structure
- Tailwind CSS configuration
- Vite frontend build setup
- Laravel testing directory included
- Standard Laravel environment configuration

---

## Tech Stack

- **PHP**
- **Laravel**
- **Laravel Breeze**
- **Blade**
- **Tailwind CSS**
- **Vite**
- **JavaScript**
- **Composer**
- **NPM**
- **PHPUnit**

---

## Architecture

The project follows Laravel’s standard MVC architecture:

- **Models** represent application data and database entities.
- **Controllers** handle request flow and application logic.
- **Routes** define how HTTP requests are mapped inside the application.
- **Views** are built using Blade templates.
- **Database files** support migrations, factories, seeders, and persistence configuration when available.
- **Public assets** are served through Laravel’s `public/` directory.
- **Frontend assets** are managed through Vite and Tailwind CSS configuration.

This structure keeps responsibilities separated and follows Laravel’s conventional organization for web applications.

---

## Project Structure

```text
laravel-breeze-crud-app/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
├── .editorconfig
├── .env.example
├── .gitattributes
├── .gitignore
├── README.md
├── artisan
├── composer.json
├── composer.lock
├── package.json
├── package-lock.json
├── phpunit.xml
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js
```

### Main Directories

- `app/`  
  Contains the core Laravel application logic, including controllers, models, and application classes.

- `bootstrap/`  
  Contains framework bootstrap files responsible for initializing the Laravel application.

- `config/`  
  Stores Laravel configuration files.

- `database/`  
  Contains database-related resources such as migrations, factories, and seeders when available.

- `public/`  
  Public entry point of the application and location for publicly accessible assets.

- `resources/`  
  Contains Blade views and frontend-related resources.

- `routes/`  
  Defines the application routes.

- `storage/`  
  Stores framework-generated files such as logs, cache, compiled files, and uploaded/generated application data when applicable.

- `tests/`  
  Contains Laravel’s default testing structure.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/lucaspc6/laravel-breeze-crud-app.git
```

Access the project directory:

```bash
cd laravel-breeze-crud-app
```

Switch to the finalized branch:

```bash
git checkout v4
```

Install PHP dependencies:

```bash
composer install
```

Install JavaScript dependencies:

```bash
npm install
```

Create the environment file:

```bash
cp .env.example .env
```

Generate the application key:

```bash
php artisan key:generate
```

Configure your database connection in the `.env` file.

Run the database migrations:

```bash
php artisan migrate
```

Build frontend assets:

```bash
npm run build
```

---

## Running the Project

Start the Laravel development server:

```bash
php artisan serve
```

If you are working in development mode, run the Vite development server in another terminal:

```bash
npm run dev
```

Open the application in your browser:

```text
http://127.0.0.1:8000
```

---

## Environment Variables

This project uses Laravel’s standard `.env` configuration file.

Common environment variables include:

```env
APP_NAME=
APP_ENV=
APP_KEY=
APP_DEBUG=
APP_URL=

DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

Update the database values according to your local development environment.

---

## Testing

The repository includes Laravel’s default testing configuration through `phpunit.xml` and the `tests/` directory.

If tests are configured in the project, they can be executed with:

```bash
php artisan test
```

---

## Screenshots

Screenshots are recommended to improve the visual presentation of this repository.

Suggested screenshots:

- Main application page
- CRUD listing page
- Create record form
- Edit record form
- Record details page, if available
- Delete confirmation flow, if available

---

## Future Improvements

Potential improvements for this project include:

- Add screenshots to the README
- Document the available routes
- Add examples of CRUD screens
- Add automated tests for CRUD flows
- Improve validation feedback in forms
- Add seed data for easier local testing
- Improve the visual documentation of the application flow
- Add a short explanation of the database tables used by the CRUD workflow

---

## Author

**Lucas Carvalho**

GitHub: [@lucaspc6](https://github.com/lucaspc6/)
