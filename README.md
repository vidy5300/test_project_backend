# Test Project Backend

A Node.js backend application for managing users, built with Express.

## Features

- RESTful API for user management
- CRUD operations for users
- UUID-based user identification

## Tech Stack

- Backend: Node.js with Express
- Database: In-memory storage (can be extended to use a database)

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd test_project_backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

Start the backend server:
```bash
npm start
```
The backend server will run on http://localhost:5000

## API Endpoints

- `GET /api/users` - Get all users
- `POST /api/users` - Create a new user
- `PUT /api/users/:id` - Update a user
- `DELETE /api/users/:id` - Delete a user

## Project Structure

```
test_project_backend/
└── server.js
``` 