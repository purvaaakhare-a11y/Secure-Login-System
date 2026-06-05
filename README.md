# 🔐 Secure Login System

A secure web-based authentication system built with Flask that provides user registration, login, password hashing, and session management.

## Features
- User registration and login
- Secure password hashing using Werkzeug
- Protection against SQL Injection using parameterized queries
- Session-based authentication
- Logout functionality
- Basic input validation
- SQLite database integration

## Setup
pip install -r requirements.txt

python database.py

python app.py

## Project Structure

secure-login-system/
├── app.py
├── database.py
├── requirements.txt
├── templates/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
└── README.md

## Concepts Covered
- Password Hashing
- User Authentication
- Session Management
- SQL Injection Prevention
- Secure Database Access
- Input Validation
- Web Security Fundamentals

## Technologies Used
- Python
- Flask
- SQLite
- Werkzeug Security

## Learning Outcomes
- Secure Authentication Design
- Web Application Security
- Session Handling
- Password Protection Techniques
- Defensive Programming