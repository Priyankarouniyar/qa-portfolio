# API Test Execution Report – JSONPlaceholder

## Project Information

| Item        | Details                     |
| ----------- | --------------------------- |
| Project     | JSONPlaceholder API Testing |
| Tool        | Postman                     |
| Tester      | Priyanka                    |
| Environment | QA Practice                 |
| API         | JSONPlaceholder User API    |

## Test Execution Summary

| Test Case  | Test Description      | Expected Status | Actual Status | Result |
| ---------- | --------------------- | --------------: | ------------: | ------ |
| API-TC-001 | Get existing user     |             200 |           200 | PASS   |
| API-TC-002 | Get non-existing user |             404 |           404 | PASS   |
| API-TC-003 | Create new user       |             201 |           201 | PASS   |
| API-TC-004 | Validate user ID      |      Correct ID |    Correct ID | PASS   |
| API-TC-005 | Validate email format |    Valid format |  Valid format | PASS   |
| API-TC-006 | Validate user name    |    Name present |  Name present | PASS   |

## Overall Result

**Total Test Cases:** 6
**Passed:** 6
**Failed:** 0

**Overall Execution Status:** PASS

## Testing Performed

* Status code validation
* Response body validation
* User ID validation
* Email format validation
* Required field testing
* Positive testing
* Negative testing
* Automated assertions using Postman
