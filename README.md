## Secure login system with SQL injection protection

#Overview:

Secure, full-stack login/registration system with SQL injection protection.
Stack: HTML, CSS, PHP, FlyEnv, and MariaDB 11.8

#Features:
- Login page for user and admin accounts, with email and password input fields.
- Registration page for new users and new admins with additional input fields.
- SQL Injection protection (prepared statements)
- Bidirectional navigation between login and registration forms.
- New account registrations stored in phpMyAdmin database (MariaDB)
- Duplicate email validation with error handling
- Password and email validation with error handling
- Admin and user pages redirect unauthenticated users to login

#Demonstration video:
https://youtu.be/yiRe-u4s29Y

#Requirements
- Visual Studio Code
- MySQL/MariaDB 11.8
- Latest verison of PHP (7.4 or higher)

#How to run
- Clone the repository
- Open in Visual Studio Code and create a file called config.php (DO NOT SKIP THIS STEP)
- Set up the database.
- Create a new database and add a users table. Make sure you have columns for: name, email, password, and role.
- Copy config.example.php to config.php, and update the database credentials.
- Start the server: php -S localhost:8000
- Then open your browser, and go to http://localhost:8000


#What I Learned
- A deeper understanding of php
- How to work with FlyEnv
- How to protect user data using prepared statements
- Debugging, debugging, debugging.
