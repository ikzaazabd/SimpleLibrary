# FinalProject1 - Simple Library Management System

This project is a simple library management system developed as part of a web application programming course. The system manages books, users, and the process of borrowing and returning books.

## Features

- **User Authentication**: Allows users to sign up, log in, and manage their account.
- **Book Management**: Users can view available books, borrow and return books.
- **Database**: The project uses a database to store user and book information.

## Folder Structure

- **.git**: Git version control for the project.
- **database**: Contains the database configuration and setup files.
- **perpus**: Contains the main application code and resources.

## Technologies Used

- **HTML/CSS/JavaScript**: Front-end development.
- **PHP**: Back-end server-side scripting.
- **MySQL**: Database for storing book and user information.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ikzaazabd/SimpleLibrary.git
2. Set up the database:
   Import the SQL files located in the database folder into your MySQL database:
   ```bash
   mysql -u <your-username> -p <your-database-name> < path/to/database.sql
3. Configure the server:
   Make sure to configure the backend according to your local setup.
   For example, if you’re using XAMPP or WAMP, place the project in the htdocs folder and configure Apache accordingly.
4. Configure the server:
   Start your local server (e.g., Apache via XAMPP/WAMP) and navigate to the project folder in your browser:
   ```bash
   http://localhost/FinalProject1/
