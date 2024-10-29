
# Student Data Management System

## Overview

This Laravel-based application is designed for managing student data, allowing users to create, view, and update records within a secure environment. The project utilizes Laravel's MVC architecture, offering a structured and efficient approach to data management.

## Features

- **Student Data Collection**: Capture essential student information.
- **Data Validation**: Built-in validation for secure and consistent data entry.
- **Database Integration**: Seamlessly stores data in a MySQL database using Laravel's Eloquent ORM.
- **CRUD Operations**: Allows Create, Read, Update, and Delete operations on student records.

## Technologies Used

- **Laravel**: Backend framework for efficient application structuring and data handling.
- **MySQL**: Database to store and retrieve student records.
- **Blade Templates**: Provides a responsive frontend using Laravel’s templating engine.

## Setup Instructions

1. **Clone Repository**: Clone this repository into your development environment.
   ```bash
   git clone https://github.com/seshamarimuthu/student-data-management-system
   ```

2. **Install Dependencies**: Navigate to the project folder and install necessary dependencies.
   ```bash
   cd student-data-management-system
   composer install
   ```

3. **Set Up Environment**: Configure your `.env` file, setting your database credentials.

4. **Database Migration**: Run the following command to set up database tables.
   ```bash
   php artisan migrate
   ```

5. **Start Application**: Use Laravel's development server to view the application.
   ```bash
   php artisan serve
   ```
Tip: When creating an admin user, set the user_type field to 'admin' in the database. This ensures the user has full access to admin-only features.

   
