# Manual Testing Bug Reports

## BUG-LOGIN-001: Unregistered Email Shows Repeated Error Messages

**Module:** Login
**Bug ID:** BUG-LOGIN-001
**Severity:** Low
**Priority:** Medium
**Status:** New
**Environment:** Google Chrome
**Test Type:** Functional Testing

### Preconditions

User is on the application login page.

### Steps to Reproduce

1. Open the login page.
2. Enter an unregistered email address.
3. Enter any password.
4. Click the **Login** button repeatedly.

### Expected Result

The system should display one clear error message indicating that the email/account was not found.

### Actual Result

Multiple error messages are displayed when the **Login** button is clicked repeatedly.

### Impact

Repeated messages make the login interface confusing and reduce the clarity of the error feedback.

### Recommendation

The application should prevent repeated error messages from being stacked when the same login action is performed repeatedly.
