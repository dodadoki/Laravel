Laravel Framework Project - Variant 2
A comprehensive web application built with Laravel framework demonstrating modern PHP development practices and the advantages of using a framework over native PHP.
 Table of Contents

About
Features
Technologies Used
Installation
Usage
Project Structure
Screenshots
Contributing
License
Contact

 About
This Laravel project serves as a demonstration of modern PHP framework development, showcasing the significant advantages of using Laravel over native PHP. The application includes comprehensive user management functionality with authentication, message handling, and dynamic interactions.
Purpose: This project demonstrates the difference between working with native PHP and a modern framework by implementing the same core features from a native PHP version (Variant 1) and enhancing them using Laravel's robust architecture and tools.
Key Objectives:

Showcase Laravel's MVC architecture and best practices
Demonstrate modern PHP development with framework benefits
Highlight improved code organization, security, and maintainability
Provide practical examples of Laravel's core features in action

 Features

User Management System

User registration with validation
Secure login/logout functionality
Password reset mechanism
Profile management


Message System

Send and receive messages
Message viewing and management
Visual differentiation by priority and status
Real-time updates via AJAX


Security & Authentication

Laravel's built-in authentication system
Middleware protection for routes
CSRF protection
Input validation and sanitization


Modern UI/UX

Responsive design with Tailwind CSS
Dynamic interactions without page reloads
Clean, professional interface
Mobile-friendly layout



 Technologies Used

Backend Framework: Laravel (PHP)
Database: MySQL
Frontend: HTML5, CSS3, JavaScript, AJAX
Styling: Tailwind CSS
Development Environment: PHPStorm

Laravel Features Utilized

Routing: Clean URL structure and RESTful routes
Blade Templating Engine: Dynamic content rendering and template inheritance
Eloquent ORM: Database interactions and model relationships
Request Validation: Form validation via Request classes
Middleware: Route protection and authentication
Authentication: Built-in user authentication system

 Installation
Prerequisites

PHP 8.0 or higher
Composer
MySQL 5.7 or higher
Web server (Apache/Nginx)
Node.js and npm (for Tailwind CSS compilation)

Steps


 Download from Google Drive
https://drive.google.com/drive/folders/1m8HZEHhrOV2JYTR8DPGV8JDJ-v5sA7TH?usp=drive_link

Download Project Files

Click the link above to access the Google Drive folder
Download all files to your local machine
Extract to your web server directory


Install PHP dependencies
bashcomposer install

Copy environment file and configure
bashcp .env.example .env

Generate application key
bashphp artisan key:generate

Configure your database connection in .env file
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password

Run database migrations
bashphp artisan migrate

Install and compile frontend assets
bashnpm install
npm run dev

Start the development server
bashphp artisan serve



Key Functionalities to Test

User Registration: Create new accounts with validation
Authentication: Login/logout functionality
Message Management: Send, receive, and organize messages
Responsive Design: Test on different screen sizes
AJAX Interactions: Experience dynamic content updates

 Project Structure
laravel-framework-project/
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   ├── Middleware/
│   │   └── Requests/
│   ├── Models/
│   └── Providers/
├── database/
│   ├── migrations/
│   └── seeders/
├── resources/
│   ├── views/
│   │   ├── layouts/
│   │   ├── auth/
│   │   └── messages/
│   ├── css/
│   └── js/
├── routes/
│   ├── web.php
│   └── api.php
├── public/
│   ├── css/
│   ├── js/
│   └── index.php
├── config/
├── storage/
├── .env.example
├── composer.json
├── package.json
└── README.md
Key Laravel Directories

app/Http/Controllers/ - Application controllers
app/Models/ - Eloquent models
app/Http/Requests/ - Form request validation
resources/views/ - Blade templates
database/migrations/ - Database schema migrations
routes/web.php - Web routes definition

 Laravel vs Native PHP Comparison
This project demonstrates the advantages of using Laravel framework over native PHP:
Laravel Advantages (Variant 2)

MVC Architecture: Clean separation of concerns
Eloquent ORM: Simplified database interactions
Blade Templating: Reusable and maintainable templates
Built-in Authentication: Secure user management out of the box
Middleware: Easy route protection and request filtering
Validation: Robust form validation via Request classes
Security: CSRF protection, input sanitization, and secure defaults

Native PHP Challenges (Variant 1)

Manual implementation of security features
Raw SQL queries and manual database management
Repetitive code for common functionalities
Limited template organization
Manual session and authentication handling


 Contributing

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

 License
This project is licensed under the MIT License - see the LICENSE file for details.
 Contact
Teodora Kuburović

Email: teakuburovic@gmail.com
GitHub: @dodadoki
LinkedIn: Teodora Kuburović


 If you found this project helpful, please give it a star!
 Educational Purpose
This project was developed as part of coursework to demonstrate the practical differences between native PHP development and modern framework usage. It serves as a learning resource for understanding Laravel's core concepts and best practices in modern PHP development.


