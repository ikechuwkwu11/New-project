# 👥 User Management API
User Management API is a simple, RESTful web service built using Django and Django REST Framework (DRF). It provides endpoints to create, read, update, and delete user records — a foundational feature in many web applications.

## ✨ Features
List All Users:
- Fetch all user records in the system.

Create New User:
- Add a new user with basic information.

Retrieve a Single User:
- Get the details of a specific user by ID.

Update User Info:
- Modify existing user data.

Delete a User:
- Permanently remove a user from the system.

## 🛠 Tech Stack
| Layer     | Technology                  |
| --------- | --------------------------- |
| Language  | Python                      |
| Framework | Django                      |
| API       | Django REST Framework (DRF) |
| Database  | SQLite (default, swappable) |


## 📫 API Endpoints
| Method | Endpoint           | Description          |
| ------ | ------------------ | -------------------- |
| GET    | `/api/users/`      | List all users       |
| POST   | `/api/users/`      | Create a new user    |
| GET    | `/api/users/<id>/` | Get a user’s details |
| PUT    | `/api/users/<id>/` | Update a user’s info |
| DELETE | `/api/users/<id>/` | Delete a user        |


## 🔐 Optional Additions
- User authentication (JWT, Token, or Session)
- Pagination and filtering
- Admin permissions and roles
- Swagger or ReDoc API documentation
