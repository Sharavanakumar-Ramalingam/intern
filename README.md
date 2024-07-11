User Management System

Description

This project implements a basic user management system with signup, login, and profile management functionalities. Users can register with a username and password, login securely using AJAX requests, and manage their profile details such as age, date of birth, and contact information. The system uses MySQL for user authentication and MongoDB for storing additional user profile details.

Features

Signup Page: Allows users to register with a username and password. Validates input and checks for existing usernames.
Login Page: Validates user credentials using AJAX requests without form submission. Maintains login session using browser local storage.
Profile Page: Displays user details fetched from MongoDB. Allows users to update their age, date of birth, and contact information.

Technologies Used

HTML5
CSS3 (Bootstrap for responsive design)
JavaScript (jQuery for AJAX)
PHP (Using Composer for dependencies)
MySQL (For user authentication)
MongoDB (For storing user profile details)

File Structure

├── index.html
├── login.html
├── profile.html
├── styles.css
├── js/
│   └── signup.js
├── php/
│   ├── db_config.php
│   ├── signup.php
│   ├── login.php
│   ├── get_profile.php
│   └── update_profile.php
├── sql/
│   └── user_db.sql
├── vendor/
│   └── (dependencies installed by Composer)
├── README.md
└── .gitignore
