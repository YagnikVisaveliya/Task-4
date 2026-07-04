# Task 1: Node.js REST API

## API Endpoints

| Method | Endpoint   | Description     |
|--------|------------|-----------------|
| GET    | /          | Welcome message |
| GET    | /health    | Health check    |
| GET    | /users     | Get all users   |
| GET    | /users/:id | Get user by ID  |
| POST   | /users     | Create user     |
| PUT    | /users/:id | Update user     |
| DELETE | /users/:id | Delete user     |

## Tests
​```bash
cd app
npm install
npm test
# 13 tests passing ✅
​```