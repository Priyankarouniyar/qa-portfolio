# Manual Test Execution Report – Login

## Project Information

| Item        | Details                |
| ----------- | ---------------------- |
| Project     | Manual Testing Project |
| Module      | Login                  |
| Tester      | Priyanka               |
| Test Type   | Functional Testing     |
| Environment | Web Application        |

## Test Execution Summary

| Test Case ID | Test Scenario                   | Expected Result                         | Result |
| ------------ | ------------------------------- | --------------------------------------- | ------ |
| TC-LOGIN-001 | Login with valid credentials    | User should log in successfully         | PASS   |
| TC-LOGIN-002 | Login with invalid password     | Login should be rejected                | PASS   |
| TC-LOGIN-003 | Login with invalid email format | Invalid email message should appear     | PASS   |
| TC-LOGIN-004 | Login with blank fields         | Email and password should be required   | PASS   |
| TC-LOGIN-005 | Login with unregistered email   | Account-not-found message should appear | PASS   |

## Execution Summary

**Total Test Cases:** 5
**Passed:** 5
**Failed:** 0

**Execution Status:** PASS

## Defect Identified

**BUG-LOGIN-001:** Repeated error messages are displayed when the Login button is clicked repeatedly for an unregistered email.

**Severity:** Low
**Priority:** Medium
**Status:** New

## Conclusion

The login test cases were executed successfully. The tested login scenarios produced the expected results, and one UI/validation defect was documented separately for further investigation.
