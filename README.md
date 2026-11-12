# User Management API Test Suite

## Overview

This project contains a Postman API test suite for a user management REST API.
It validates core user operations, response structure, and error handling.

## Tools Used

- Postman
- JSONPlaceholder API
- Postman Collection Runner
- JavaScript test scripts

## What Is Tested

### Positive tests
- Retrieve all users
- Retrieve a user by ID
- Create a user
- Update a user
- Delete a user

### Negative tests
- Retrieve a nonexistent user
- Submit invalid user data


## Test Coverage

| Area | Tests |
|---|---|
| Status codes | 200, 201, 404 |
| Response body | Field presence, data types, expected values |
| Error handling | Missing resources and invalid input |
| Workflow | Create then retrieve a user |
| Automation | Full collection run using Collection Runner |

## How to Run

1. Download and install Postman.
2. Import `user-management-api-tests.postman_collection.json`.
3. Import `test-environment.postman_environment.json`.
4. Select the `Test Environment`.
5. Open the collection and click **Run**.
6. Review the test results.


## What I Learned

- Designing API tests beyond basic status-code checks
- Validating JSON response structure and values
- Using variables and request chaining
- Creating positive and negative test cases
- Running an API test suite with Postman Collection Runner
