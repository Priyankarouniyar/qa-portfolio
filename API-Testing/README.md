# API Testing – JSONPlaceholder

## Project Overview

This project demonstrates practical API testing using **Postman** and the **JSONPlaceholder User API**.

The project covers positive and negative API testing, response validation, environment variables, and automated test assertions.

## Objectives

* Understand API testing using Postman
* Test different HTTP methods
* Validate HTTP status codes
* Validate API response data
* Perform positive and negative testing
* Use environment variables
* Create automated API assertions

## Tools & Technologies

* **Postman**
* **JavaScript** – for automated test assertions
* **GitHub** – for test documentation and portfolio

## API Tested

**JSONPlaceholder User API**

Base URL:

`https://jsonplaceholder.typicode.com`

## HTTP Methods Tested

* GET
* POST

## Testing Performed

* Positive testing
* Negative testing
* Status code validation
* Response body validation
* User ID validation
* Email format validation
* Required field testing
* Environment variable testing
* Automated assertions

## Test Scenarios

| Test Scenario             | Expected Result                    | Result             |
| ------------------------- | ---------------------------------- | ------------------ |
| Get existing user         | 200 OK                             | PASS               |
| Validate user ID          | Correct ID returned                | PASS               |
| Validate email format     | Valid email format                 | PASS               |
| Validate user name        | Name is present                    | PASS               |
| Get non-existing user     | 404 Not Found                      | PASS               |
| Create new user           | 201 Created                        | PASS               |
| Create user without email | API should validate required field | FAIL / Observation |

## Postman Assertions

Automated assertions were created to validate:

* HTTP status codes
* User ID
* Email format
* User name
* Response body

## Project Structure

```text
API-Testing/
│
├── README.md
├── API-Test-Cases.md
├── Bug-Reports.md
└── Test-Execution-Report.md
```

## Key Learning

Through this project, I gained practical experience in API testing, writing test cases, performing negative testing, validating API responses, and creating automated assertions in Postman.
