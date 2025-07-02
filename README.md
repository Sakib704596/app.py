# app.py
# Flask REST API - User Management

This is a simple RESTful API built with Flask that allows managing user data using in-memory storage.

## Endpoints

- `GET /users` → List all users
- `GET /users/<id>` → Get user by ID
- `POST /users` → Add a new user
- `PUT /users/<id>` → Update user
- `DELETE /users/<id>` → Delete user

## Sample POST JSON
```json
{
  "id": 1,
  "name": "Sakib",
  "email": "sakib@example.com"
}

