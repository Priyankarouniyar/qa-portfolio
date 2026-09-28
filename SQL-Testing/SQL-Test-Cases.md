# SQL Test Cases

## Test Case 1 – Verify User Record

**Test Case ID:** SQL-TC-001
**Test Scenario:** Verify that a user record exists in the database
**SQL Query:**

```sql
SELECT * FROM users WHERE email = 'priyanka@example.com';
```

**Expected Result:**
The user's record should be displayed with the correct name, email, and other stored information.

**Status:** PASS

---

## Test Case 2 – Verify User Data

**Test Case ID:** SQL-TC-002
**Test Scenario:** Verify that the stored user name matches the expected value
**SQL Query:**

```sql
SELECT name FROM users WHERE email = 'priyanka@example.com';
```

**Expected Result:**
The correct user name should be returned.

**Status:** PASS

---

## Test Case 3 – Verify Updated Data

**Test Case ID:** SQL-TC-003
**Test Scenario:** Verify that updated user information is correctly stored
**SQL Query:**

```sql
SELECT email FROM users WHERE id = 1;
```

**Expected Result:**
The updated email should be displayed correctly.

**Status:** PASS

---

## Test Case 4 – Verify Deleted Record

**Test Case ID:** SQL-TC-004
**Test Scenario:** Verify that a deleted user record no longer exists
**SQL Query:**

```sql
SELECT * FROM users WHERE id = 999;
```

**Expected Result:**
No record should be returned for the deleted user.

**Status:** PASS

---

## Test Case 5 – Check Duplicate Emails

**Test Case ID:** SQL-TC-005
**Test Scenario:** Identify duplicate email addresses
**SQL Query:**

```sql
SELECT email, COUNT(*)
FROM users
GROUP BY email
HAVING COUNT(*) > 1;
```

**Expected Result:**
Only email addresses appearing more than once should be displayed.

**Status:** PASS

---

## Summary

| Test Case  | Description            | Status |
| ---------- | ---------------------- | ------ |
| SQL-TC-001 | Verify user record     | PASS   |
| SQL-TC-002 | Verify user data       | PASS   |
| SQL-TC-003 | Verify updated data    | PASS   |
| SQL-TC-004 | Verify deleted record  | PASS   |
| SQL-TC-005 | Check duplicate emails | PASS   |
