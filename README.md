# Simple Group Chat Application

This repository contains the code for a simple group chat application, which is similar to the one seen in WhatsApp messenger, but running on a localhost server. Multiple users can join the chat and share their messages. The application uses MySQL to store and retrieve messages.

## Prerequisites

### Technical Knowledge

Before setting up the application, you should have a basic understanding of:

- HTML
- CSS
- JavaScript (basics)
- PHP (Database connectivity)
- SQL queries

### Software Requirements

You will need to install the following software:

1. **XAMPP Server**
   - XAMPP is a free and open-source cross-platform web server solution stack package developed by Apache Friends, consisting mainly of the Apache HTTP Server, MariaDB database, and interpreters for scripts written in the PHP and Perl programming languages.
   - Download XAMPP from the official [Apache Friends website](https://www.apachefriends.org/index.html).

2. **phpMyAdmin**
   - phpMyAdmin is a free and open-source tool written in PHP, intended to handle the administration of MySQL over the Web. It can perform various tasks such as creating, modifying, or deleting databases, tables, fields, or rows; executing SQL statements; or managing users and permissions.
   - Download phpMyAdmin from the official [phpMyAdmin website](https://www.phpmyadmin.net/).
   - After downloading, unzip the phpMyAdmin files and place the folder in the following location:
     ```plaintext
     C:\xampp\htdocs
     ```
   - Unzipping the file anywhere else won’t work correctly. Just unzip the contents in the specified location.

3. **Text Editor**
   - Any text editor like Notepad++ or even the default Notepad will suffice for editing code files.

4. **Web Browser**
   - Any JavaScript-enabled web browser (such as Chrome, Firefox, or Edge) will be adequate for running and testing the application.

## Application Overview

The group chat application is designed to simulate a basic chatroom where users can share messages. The interface consists of two main fields: the username and the text message. Messages from the user who sends a message first will be aligned to the right side of the chatroom, while messages from other users will be aligned to the left side.

### Implementation Details

To implement this application, you will need to create:

- **HTML**: To structure the web pages.
- **CSS**: To style the user interface.
- **JavaScript**: To add interactivity.
- **PHP**: For server-side logic to store and retrieve messages from the database.

### Setting Up the Application

1. **Start XAMPP**: Open the XAMPP control panel and start the Apache and MySQL modules.
2. **Create Database**: Use phpMyAdmin to create a new database for the chat application. Create the necessary tables to store chat messages and user information.
3. **Clone Repository**: Clone this repository into the `htdocs` directory of your XAMPP installation.
4. **Configure Database Connection**: Update the PHP files to configure the database connection details (such as database name, username, and password).
5. **Run the Application**: Open your web browser and navigate to `http://localhost/your-repository-folder` to access the chat application.

## Conclusion

By following the instructions above, you should be able to set up and run the simple group chat application on your local server. This project is a great way to get hands-on experience with web development technologies and build a functional chat application.

Happy Coding!
