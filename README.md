# My Swagger API Documentation

This is the documentation for my first Swagger API specifications. The API provides endpoints for managing students and teachers.

## SWAGGER UI

The API can be used in Swagger UI at:

```https://petstore.swagger.io/?url=https://raw.githubusercontent.com/AndyPendragon/first-swagger-specs/main/openapi.yaml```

## Endpoints

### /students

The `/students` endpoint allows you to interact with student resources.

#### GET /students

Retrieve a list of all students.

#### POST /students

Add a new student to the system.

### /teachers

The `/teachers` endpoint allows you to interact with teacher resources.

#### GET /teachers

Retrieve a list of all teachers.

#### POST /teachers

Add a new teacher to the system.

## How to Use

You can use tools like [Swagger UI](https://swagger.io/tools/swagger-ui/) or [Postman](https://www.postman.com/) to interact with the API endpoints and see the responses.

## Example Requests

### Show the Student

```http
https://petstore.swagger.io/?url=https://raw.githubusercontent.com/AndyPendragon/first-swagger-specs/main/openapi.yaml#/default/get_students
```

### Add a New Student

```http
POST https://petstore.swagger.io/?url=https://raw.githubusercontent.com/AndyPendragon/first-swagger-specs/main/openapi.yaml#/default/post_students

{
  "id": "1",
  "name": "Rakoto",
  "birthdate": "2000-01-01"
}
```