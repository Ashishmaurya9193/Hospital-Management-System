# Hospital Management System

A full-stack Hospital Management System built with Java and Spring Boot. Supports managing hospitals, patients, and appointments via RESTful APIs.

## Features
- Add, view, update, and delete hospitals and patients
- API endpoints documented and tested with Postman
- Spring Boot + JPA (and MongoDB in advanced modules)
- Modular code structure

## Getting Started

1. Clone the repo
2. Run `mvn clean install`
3. Start the application: `mvn spring-boot:run`
4. Use the provided Postman/curl commands to test endpoints

## API Endpoints

- `POST /hospital/save` — Add a new hospital
- `GET /hospital/get` — Retrieve hospitals
- `PUT /hospital/update` — Update hospital details
- `DELETE /hospital/delete` — Remove a hospital
- Similar endpoints for patients

## Improvements in Progress
- Adding authentication/authorization
- Docker support for easier deployment
- API documentation via Swagger
