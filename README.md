# User Management System – Backend

## Introduction

This is the **backend** of the User Management System, developed using **Node.js** with **MySQL**. It provides all necessary API endpoints to support user authentication, role-based access, email verification, password recovery, and admin account management. It is designed to integrate seamlessly with the Angular frontend.

### Key Features (Backend Only)

-  Email sign-up and verification
-  JWT authentication with refresh tokens
-  Role-based authorization (Admin and User roles)
-  Forgot password and reset password functionality
-  CRUD operations for managing accounts (Admin access only)

---

## Installation Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/user-management-system.git
cd user-management-system/backend


Install dependencies
--npm install

Set up environment variables
Create a .env file in the backend directory and add the following:

JWT_SECRET=your-super-secret-key-here
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASS=
DB_NAME=node-mysql-signup-verification-api

Start the backend server
--npm start

Usage
Register a new account
POST /accounts/register
Body: { "firstName": "", "lastName": "", "email": "", "password": "" }

Verify your email
Click the verification link sent via email.

Authenticate (Login)
POST /accounts/authenticate
Body: { "email": "", "password": "" }

Refresh token
POST /accounts/refresh-token
Header: Authorization: Bearer <refresh_token>

Forgot/Reset password
POST /accounts/forgot-password
Body: { "email": "" }

POST /accounts/reset-password
Body: { "token": "", "password": "" }

Admin-only: Manage user accounts
GET /accounts – List all users

GET /accounts/:id – Get user by ID

PUT /accounts/:id – Update user

DELETE /accounts/:id – Delete user

Testing
Functional Testing Includes
Registration and email verification

Authentication and token refresh

Role-based access control

Password reset flow

Admin-only account management

Use tools like Postman or Insomnia to test endpoints manually.

Contributing
Use descriptive branches: backend-signup-auth, backend-crud, etc.

Commit frequently with meaningful messages

Submit a PR to merge features into the main branch

Pull from main regularly to avoid conflicts