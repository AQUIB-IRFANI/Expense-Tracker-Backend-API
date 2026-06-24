# Expense Tracker Backend

A secure and scalable backend application for managing personal expenses. The application provides user authentication and expense management features through RESTful APIs built with Node.js, Express.js, and MongoDB.

## Features

- User Registration
- User Login Authentication
- Secure Password Hashing using bcrypt
- Session-Based Authentication
- Expense Management (CRUD Operations)
- Protected Routes
- Input Validation
- MongoDB Database Integration
- RESTful API Architecture
- MVC Architecture

## Tech Stack

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Security
- bcrypt

### Tools
- Postman
- Git
- GitHub

## Project Structure

```text
expense-tracker-backend
│
├── controllers
├── models
├── routes
├── middleware
├── config
├── server.js
├── package.json
└── README.md
```

## API Endpoints

### Authentication

| Method | Endpoint | Description |
|----------|----------|----------|
| POST | /api/auth/register | Register User |
| POST | /api/auth/login | Login User |
| POST | /api/auth/logout | Logout User |

### Expenses

| Method | Endpoint | Description |
|----------|----------|----------|
| GET | /api/expenses | Get All Expenses |
| POST | /api/expenses | Add Expense |
| PUT | /api/expenses/:id | Update Expense |
| DELETE | /api/expenses/:id | Delete Expense |

## Installation

### Clone Repository

```bash
git clone https://github.com/AQUIB-IRFANI/expense-tracker-backend.git
```

### Install Dependencies

```bash
npm install
```

### Create Environment Variables

Create a .env file

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
```

### Start Application

```bash
npm start
```

## API Testing

The APIs can be tested using:

- Postman
- Thunder Client

## Key Learning Outcomes

- Backend Development with Node.js and Express.js
- REST API Design
- Authentication and Authorization
- MongoDB Data Modeling
- MVC Architecture
- Git Version Control
- Debugging and Testing

## Author

Aquib Muzzammil Irfani

GitHub:
https://github.com/AQUIB-IRFANI

LinkedIn:
https://linkedin.com/in/aquib-irfani-422746253
