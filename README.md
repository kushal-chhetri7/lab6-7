 Project Overview
This project is a hands-on introduction to the Laravel PHP framework. It includes setting up a new Laravel project, exploring its file structure, creating routes and controllers, and developing dynamic views using Blade templating. The goal is to gain practical experience with Laravel’s core features, preparing for more advanced web development projects.

Learning Objectives
By the end of this lab, you will be able to:

Understand Laravel Fundamentals: Recognize the benefits and structure of a Laravel project.

Set Up a Laravel Project: Install Laravel via Composer and navigate the project’s directory structure.

Implement Routing and Controllers: Define routes and create controllers to handle HTTP requests.

Develop Dynamic Views: Create and modify Blade templates to display dynamic content.

Utilize Artisan CLI: Employ Laravel’s command-line interface for routine tasks, such as generating controllers and migrations.

Apply Best Practices: Follow Laravel conventions to ensure maintainable and scalable code.

Project Setup
Prerequisites
PHP (version 7.4 or higher)

Composer (PHP dependency manager)

Terminal or Command Line Interface (CLI)

Installation Steps
Install Laravel:
Open your terminal and run:

bash
Copy
composer create-project --prefer-dist laravel/laravel lab6-7
Navigate to the Project Directory:

bash
Copy
cd lab6-7
Run the Development Server:
Start Laravel's built-in server:

bash
Copy
php artisan serve
Then, access the project in your browser at http://localhost:8000.

Explore the Directory Structure:
Familiarize yourself with key folders:

/routes (especially web.php)

/app/Http/Controllers

/resources/views

/database/migrations
