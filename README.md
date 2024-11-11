# User Management API

A .NET Core 8 Web API project that provides CRUD operations for user management.

## Features

- Full CRUD operations for Users
- In-memory database using Entity Framework Core
- Input validation
- Error handling and logging
- Swagger documentation

## API Endpoints

- GET /api/users - Get all users
- GET /api/users/{id} - Get a specific user
- POST /api/users - Create a new user
- PUT /api/users/{id} - Update an existing user
- DELETE /api/users/{id} - Delete a user

## Business Rules

- FirstName: Required, max length 128
- LastName: Optional, max length 128
- Email: Required, must be unique and valid
- DateOfBirth: Required, user must be 18 or older
- PhoneNumber: Required, must be exactly 10 digits

## Getting Started

1. Clone the repository
2. Open the solution in Visual Studio or VS Code
3. Run the project
4. Access Swagger UI at https://localhost:7xxx/swagger

## Technologies

- .NET Core 8
- Entity Framework Core
- Swagger/OpenAPI 