# Manual Testing Test Scenarios – Login

## Login Test Scenarios

| Scenario ID  | Test Scenario                                               | Priority |
| ------------ | ----------------------------------------------------------- | -------- |
| TS-LOGIN-001 | Verify login with valid email and valid password            | High     |
| TS-LOGIN-002 | Verify login with valid email and invalid password          | High     |
| TS-LOGIN-003 | Verify login with invalid email format                      | Medium   |
| TS-LOGIN-004 | Verify login with blank email and password                  | High     |
| TS-LOGIN-005 | Verify login with unregistered email                        | Medium   |
| TS-LOGIN-006 | Verify password field is masked                             | Medium   |
| TS-LOGIN-007 | Verify password visibility/show option                      | Low      |
| TS-LOGIN-008 | Verify login button behavior with blank fields              | High     |
| TS-LOGIN-009 | Verify email field rejects leading/trailing spaces          | Medium   |
| TS-LOGIN-010 | Verify login using uppercase email characters               | Medium   |
| TS-LOGIN-011 | Verify login with a very long email address                 | Low      |
| TS-LOGIN-012 | Verify Forgot Password functionality                        | High     |
| TS-LOGIN-013 | Verify multiple invalid login attempts                      | High     |
| TS-LOGIN-014 | Verify appropriate error message for invalid credentials    | Medium   |
| TS-LOGIN-015 | Verify successful login redirects the user to the dashboard | High     |

## Testing Coverage

The scenarios cover:

* Positive login testing
* Negative login testing
* Input validation
* Password field behavior
* Error message validation
* Login security-related behavior
* Forgot password functionality
* Boundary and unusual input testing
* Navigation after successful login
