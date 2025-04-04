# Assignment-3
# Student data Management API

A RESTful API built with Flask for managing student records with full CRUD functionality.

## Features

- Create, Read, Update, and Delete student records
- SQLite database with SQLAlchemy ORM
- RESTful endpoints with JSON responses
- Error handling and validation

## API Endpoints

| Method | Endpoint         | Description                     |
|--------|------------------|---------------------------------|
| POST   | /students        | Create a new student record     |
| GET    | /students        | Get all student records         |
| GET    | /students/<id>   | Get a specific student record   |
| PUT    | /students/<id>   | Update a student record         |
| DELETE | /students/<id>   | Delete a student record         |

## Request/Response Examples

### Create Student (POST /students)
**Request:**
```json
{
        "amount_due": 1200.5,
        "dob": "1999-08-22",
        "first_name": "Karthik",
        "last_name": "S",
        "student_id": 6
}
