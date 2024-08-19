# Laravel Basic CRUD Application

## Overview

This is a simple Laravel application designed to perform CRUD (Create, Read, Update, Delete) operations for managing products. It utilizes a MySQL database to handle product information.

## Features

- **Create:** Add new products to the database.
- **Read:** View a list of all products and details of individual products.
- **Update:** Modify existing product details.
- **Delete:** Remove products from the database.

## Prerequisites

- PHP 8.0 or higher
- Composer
- Laravel 9.x or higher
- MySQL database

## Installation

Follow these steps to set up the application on your local environment:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/laravel-crud-app.git
   cd laravel-crud-app
   ```

2. **Install Dependencies:**

   ```bash
   composer install
   ```

3. **Set Up Environment:**

   Copy the `.env.example` file to `.env`:

   ```bash
   cp .env.example .env
   ```

   Open the `.env` file and configure your MySQL database settings:

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_database_user
   DB_PASSWORD=your_database_password
   ```

4. **Generate Application Key:**

   ```bash
   php artisan key:generate
   ```

5. **Run Migrations:**

   ```bash
   php artisan migrate
   ```

6. **Serve the Application:**

   ```bash
   php artisan serve
   ```

   The application will be available at [http://localhost:8000](http://localhost:8000).

## Usage

Once the application is running, you can access the following features:

- **Dashboard:** View and manage all products.
- **Product Details:** View detailed information about individual products.
- **Edit Product:** Update product details.
- **Delete Product:** Remove products from the list.
