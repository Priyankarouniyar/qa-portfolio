# Manual Test Cases – Login Functionality

## Test Case 1: Login with Valid Credentials

**Test Case ID:** TC-LOGIN-001
**Test Scenario:** Verify login with valid email and password
**Priority:** High

**Precondition:** User has a registered account.

**Test Steps:**

1. Open the login page.
2. Enter a valid registered email.
3. Enter the correct password.
4. Click the **Login** button.

**Expected Result:**
User should be logged in successfully and redirected to the dashboard/home page.

**Test Data:**

* Email: `test@example.com`
* Password: `ValidPassword123`

**Result:** PASS

---

## Test Case 2: Login with Invalid Password

**Test Case ID:** TC-LOGIN-002
**Test Scenario:** Verify login with valid email and invalid password
**Priority:** High

**Test Steps:**

1. Open the login page.
2. Enter a registered email.
3. Enter an incorrect password.
4. Click the **Login** button.

**Expected Result:**
User should not be logged in and an appropriate invalid-credentials message should be displayed.

**Result:** PASS

---

## Test Case 3: Login with Invalid Email Format

**Test Case ID:** TC-LOGIN-003
**Test Scenario:** Verify login with invalid email format
**Priority:** Medium

**Test Steps:**

1. Open the login page.
2. Enter an invalid email such as `test@`.
3. Enter a valid password.
4. Click the **Login** button.

**Expected Result:**
The system should display an appropriate message indicating that the email format is invalid.

**Result:** PASS

---

## Test Case 4: Login with Blank Fields

**Test Case ID:** TC-LOGIN-004
**Test Scenario:** Verify login without entering email and password
**Priority:** High

**Test Steps:**

1. Open the login page.
2. Leave the email field empty.
3. Leave the password field empty.
4. Click the **Login** button.

**Expected Result:**
The system should require the user to enter both email and password.

**Result:** PASS

---

## Test Case 5: Login with Unregistered Email

**Test Case ID:** TC-LOGIN-005
**Test Scenario:** Verify login using an unregistered email
**Priority:** Medium

**Test Steps:**

1. Open the login page.
2. Enter an email that is not registered.
3. Enter a password.
4. Click the **Login** button.

**Expected Result:**
The system should not allow login and should display an appropriate message indicating that the email/account was not found.

**Result:** PASS
