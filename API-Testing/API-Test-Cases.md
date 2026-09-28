# API Test Cases – JSONPlaceholder

## API-TC-001: Get Existing User

**Method:** GET
**Endpoint:** `{{baseUrl}}/users/{{userId}}`

**Test Steps:**

1. Set `userId` to `1`.
2. Send the GET request.
3. Verify the response.

**Expected Result:**

* Status code should be **200 OK**.
* User ID should match the requested ID.
* User name should be present.
* Email should have a valid format.

**Status:** PASS

---

## API-TC-002: Get Non-Existing User

**Method:** GET
**Endpoint:** `{{baseUrl}}/users/999`

**Test Steps:**

1. Send a GET request for user ID `999`.
2. Verify the response.

**Expected Result:**

* Status code should be **404 Not Found**.
* Response body should be empty `{}`.

**Status:** PASS

---

## API-TC-003: Create New User

**Method:** POST
**Endpoint:** `{{baseUrl}}/users`

**Request Body:**

```json
{
    "name": "Priyanka",
    "username": "priyankaQA",
    "email": "priyanka@example.com"
}
```

**Expected Result:**

* Status code should be **201 Created**.
* Created user's name should be `Priyanka`.
* Response should contain the created user information.

**Status:** PASS
