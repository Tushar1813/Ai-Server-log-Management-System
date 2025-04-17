# Ai-Server-log-Management-System
An AI system to collect, store, analyze, and query server logs using smart insights.
# AI LogMaster

A modern web application for managing and tracking AI-related logs and activities.

## Features

- User authentication system
- Secure login and signup functionality
- Modern, responsive UI with glassmorphism design
- Tailwind CSS for styling
- MySQL database integration

## Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- XAMPP or similar local development environment
- Web server (Apache recommended)

## Installation

1. Clone the repository to your local machine
2. Import the database schema from `database.sql` (if provided)
3. Configure your database connection in the relevant PHP files:
   - Update `$servername`, `$username`, `$password`, and `$dbname` in the database connection files
4. Place the project files in your web server's root directory (e.g., `htdocs` for XAMPP)
5. Start your local server (Apache and MySQL)

## Project Structure

```
Project FS/
├── login.php          # Login page with authentication
├── signup.php         # User registration page
├── index.php          # Main application page
└── database/          # Database related files
```

## Security Features

- Password hashing using PHP's `password_hash()` and `password_verify()`
- Prepared statements to prevent SQL injection
- Input sanitization using `htmlspecialchars()`
- Session management for user authentication

## Technologies Used

- PHP
- MySQL
- HTML5
- Tailwind CSS
- JavaScript

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or support, please contact the project maintainers. 
