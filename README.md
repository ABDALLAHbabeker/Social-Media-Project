
# Our Social Media Platform

## Description

This project is a social media platform built using MySQL, HTML, PHP, and Bootstrap. It allows users to register, login, create and view posts, add comments, and like posts. Additionally, it includes an admin role that can manage user registration.

## Prerequisites

- **Web Server:** Apache, Nginx, or MAMP/XAMPP.
- **MySQL Database:** Install and configure a MySQL database server.
- **PHP:** Version 7.2 or later (check with `php -v`).
- **Composer:** Install Composer to manage PHP dependencies: https://getcomposer.org/

## Installation

1. **Clone the Repository:**

   ```bash 
   git clone [https://github.com/your-username/your-repository-name.git]
   ```
  2. **Set Up Database:**
  -   Create a new database for your project using your MySQL administration tool (e.g., phpMyAdmin).
-   Edit the `config.php` file within your project directory and update the following details with your database credentials:
	```php
	$db_host = 'localhost';
	$db_name = 'your_database_name';
	$db_user = 'your_database_username';
	$db_password = 'your_database_password';
	```
   4. **Create Database Tables:**
   - Export the SQL Database to your MySQL client (e.g., phpMyAdmin) 
   you will find the database in the files of this project
   
   5. **Start the Web Server:**
   -   Start your web server (Apache, Nginx, or MAMP/XAMPP) and configure it to serve the project directory.
-   Consult your web server's documentation for specific configuration instructions.
   6. **Access the Platform:**
   -   Open your web browser and navigate to: `http://localhost/[your-project-directory]`

**Note:** Replace `[your-project-directory]` with the actual directory name where your project resides on your local machine.

## Usage

-   Users can register for an account and log in using the provided forms.
-   Logged-in users can:
    -   View their own and other users' posts.
    -   Create new posts.
    -   Add comments to existing posts.
    -   Like and dislike posts.
-   Administrators can manage user registration through a dedicated admin panel.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
