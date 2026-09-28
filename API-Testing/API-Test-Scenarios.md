# API Test Scenarios – JSONPlaceholder

## 1. User Retrieval Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| API-TS-001 | Retrieve an existing user | API should return 200 OK with user details |
| API-TS-002 | Retrieve user using different user IDs | API should return the correct user for the given ID |
| API-TS-003 | Retrieve a non-existing user | API should return 404 Not Found |
| API-TS-004 | Verify user ID in response | Response user ID should match the requested ID |

## 2. User Creation Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| API-TS-005 | Create a user with valid data | API should return 201 Created |
| API-TS-006 | Create a user with missing email | API should validate the missing required field |
| API-TS-007 | Create a user with missing name | API should validate the missing required field |
| API-TS-008 | Create a user with missing username | API should validate the missing required field |

## 3. Response Validation Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| API-TS-009 | Verify response status code | Status code should match the expected result |
| API-TS-010 | Verify user name is present | User name should be available in the response |
| API-TS-011 | Verify email format | Email should follow a valid email format |
| API-TS-012 | Verify response body structure | Response should contain the expected fields |

## 4. Negative Testing Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| API-TS-013 | Request a non-existing user ID | API should return 404 Not Found |
| API-TS-014 | Send incomplete user data | API should validate the missing fields |
| API-TS-015 | Send invalid request data | API should return an appropriate validation response |

## Testing Approach

The API testing scenarios cover both **positive and negative testing**.

### Positive Testing
- Valid user ID
- Valid user data
- Successful user creation
- Valid response structure
- Valid email format

### Negative Testing
- Non-existing user ID
- Missing required fields
- Incomplete request data
- Invalid request data

## Tools Used

- Postman
- JSONPlaceholder API
- GitHub
- JavaScript assertions

## Status

**Completed**
