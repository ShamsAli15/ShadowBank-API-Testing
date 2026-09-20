# ShadowBank API Testing

A comprehensive API testing project for a mobile banking application using **Postman**.

## Project Overview

This project focuses on testing the REST APIs of the ShadowBank mobile banking application, covering functional, negative, security, edge-case, and end-to-end scenarios.

## Tools & Technologies

* Postman
* Swagger
* REST APIs
* JSON
* JavaScript (Postman Scripts)
* Excel
* Spring Boot
* H2 Database

## Project Structure

```text
ShadowBank/
├── Backend/
├── Frontend/
├── Postman/
│   ├── Mobile Banking API - Happy & Bad Path Tests.postman_collection.json
│   └── Project Banking.postman_environment.json
└── Test Cases/
    └── Test Cases for Mobile Banking_.xlsx
```

## API Testing Coverage

The Postman collection includes testing for:

* Users
* Accounts
* Transactions
* Authentication
* Positive scenarios
* Negative scenarios
* Validation
* Edge cases
* Security testing
* Data-driven testing
* End-to-end scenarios

## Postman Testing

The project uses Postman scripts for:

* Status code validation
* Response body validation
* JSON field validation
* Dynamic test data generation
* Environment variables
* Pre-request scripts
* Post-response test scripts
* Data-driven testing

## Test Cases

Detailed test cases are maintained in an Excel file and cover different testing categories, including:

* Functional Testing
* Negative Testing
* Security Testing
* Edge Cases
* Usability Testing
* Accessibility Testing
* Compatibility Testing
* End-to-End Testing

## How to Run

1. Clone the repository.
2. Open Postman.
3. Import the collection from the `Postman` folder.
4. Import the environment file.
5. Select the appropriate environment.
6. Make sure the ShadowBank backend is running.
7. Run individual requests or execute the collection using the Postman Collection Runner.

## Notes

This project was created for API testing practice and QA portfolio purposes.

All test data and credentials included in the repository should be non-sensitive and intended for local testing only.
