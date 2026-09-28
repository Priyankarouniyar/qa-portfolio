# API Bug Reports – JSONPlaceholder

## BUG-API-001: Non-Existing User Returns 404

**API:** Get User
**Method:** GET
**Endpoint:** `{{baseUrl}}/users/999`

**Steps to Reproduce:**

1. Set the `userId` to `999`.
2. Send the GET request.
3. Observe the response.

**Expected Result:**
The API should return **404 Not Found** for a user that does not exist.

**Actual Result:**
The API returned **404 Not Found**.

**Status:** Not a Bug – Expected Behavior

---

## BUG-API-002: Empty Request Fields

**API:** Create User
**Method:** POST
**Endpoint:** `{{baseUrl}}/users`

**Test Data:**

```json
{
    "name": "Priyanka",
    "username": "priyankaQA"
}
```

**Expected Result:**
The API should reject the request with a validation error because the email field is missing.

**Actual Result:**
The API returned **201 Created** even though the email field was missing.

**Severity:** Medium
**Priority:** Medium
**Status:** Open

**Observation:**
The API accepted incomplete user data without validating the required email field.
