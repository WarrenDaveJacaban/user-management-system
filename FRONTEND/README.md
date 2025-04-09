# user-management-system-frontend  
**Group Project Activity: Full-Stack App Development – FRONTEND (Angular.js)**

---

## Introduction  
The **User Management System** is a dynamic web application aimed at simplifying user registration, login, and account access control. It offers a secure platform to manage users through different roles, with proper authentication and authorization features.

Developed using **Angular** for the frontend, and powered by a **Node.js + MySQL** backend, the system supports essential functionalities such as JWT login, email confirmation, password recovery, profile editing, and admin-level user control. A built-in mock backend allows smooth development without the need for a live server during testing.

The system is packed with practical features like email registration and verification, secure login via tokens, user roles, profile updates, and admin account tools — all built into an Angular-ready framework for modern frontend development.

### Developed by:
- **Chan**
- **Carungay**

---

## Installation Steps

1. **Clone the repository:**
   ```bash
   git clone 
2. **Install necessary packages:**
    npm install
3. **Start the backend server:**
    npm start
4. **Run the Angular app:**
    ng serve

## How to Use
For Regular Users:
Register via /account/register

Activate your account using the email verification link

Sign in through /account/login

Edit your profile by visiting /profile/update

For Admin Users:
Login through /account/login using admin credentials

Navigate to /admin/accounts/list to access the admin dashboard

Perform CRUD operations on users via /admin/accounts/add-edit

Testing Summary
Function Testing: Scenarios for sign-up, login, password reset, and access control have been validated.

Security Checks: Routes are protected, JWT handling is verified, and forms follow proper validation rules.

Code Review: Ensured quality through structured components and proper commenting.

Test Documentation: Full test reports can be added here once available (insert your link).


## Contribution Workflow
## Developer 3 – Carungay
Role: Email Sign-Up, Verification, and Authentication

Branch: carungay-frontend-auth

Steps:
git checkout -b carungay-frontend-auth
git add .
git commit -m "Implemented email sign-up and authentication"
git push origin carungay-frontend-auth

## Developer 4 – Chan
Role: Profile Management, Admin Dashboard, Fake Backend

Branch: chan-frontend-dashboard-fakebackend

Steps:
git checkout -b chan-frontend-dashboard-fakebackend
git add .
git commit -m "Created admin dashboard and fake backend implementation"
git push origin chan-frontend-dashboard-fakebackend
After pushing, both developers will open a Pull Request and request review before merging into main.

