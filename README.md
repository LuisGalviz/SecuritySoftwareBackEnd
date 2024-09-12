# Secure Web Application - Backend

## Project Overview
This repository contains the backend for a secure web application built using NestJS. The application follows OWASP best practices and incorporates cryptographic libraries for added security. It manages user authentication, AES file encryption/decryption, and secure session handling.

## Features
- **User Registration**: Secure registration system with password validation (minimum 8 characters, 1 number, 1 uppercase, 1 lowercase, 1 special character).
- **User Login**: Secure login using password hashing with SHA-1.
- **User Data Management**: Store and manage user data, including username, name, and securely hashed password.
- **AES File Encryption/Decryption**: Upload files for encryption or decryption using AES with a provided key.
- **Download User Data**: Provides an endpoint to download a table of users in text format (including hashed passwords).
- **Secure Logout**: Ensure session termination with a safe logout mechanism.

## Tech Stack
- **NestJS**: Framework for building efficient, scalable server-side applications with Node.js.
- **TypeORM**: Database ORM for handling relational databases.
- **Bcrypt**: For hashing and verifying passwords.
- **Crypto**: For AES encryption and decryption.
- **OWASP ZAP**: Used for security vulnerability testing and compliance with OWASP best practices.
