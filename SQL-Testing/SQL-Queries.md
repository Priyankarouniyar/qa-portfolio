# SQL Queries – QA Practice

This document contains SQL queries commonly used by QA testers for database validation.

## 1. View All Users

```sql
SELECT * FROM users;
```

**Purpose:** Verify all records stored in the users table.

---

## 2. Find a User by ID

```sql
SELECT * FROM users
WHERE id = 1;
```

**Purpose:** Verify a specific user's database record.

---

## 3. Find a User by Email

```sql
SELECT * FROM users
WHERE email = 'priyanka@example.com';
```

**Purpose:** Verify whether a specific email exists in the database.

---

## 4. Select Specific Columns

```sql
SELECT name, email
FROM users;
```

**Purpose:** Verify specific fields instead of retrieving the complete record.

---

## 5. Insert a New User

```sql
INSERT INTO users (name, email)
VALUES ('Priyanka', 'priyanka@example.com');
```

**Purpose:** Verify that new user data can be inserted into the database.

---

## 6. Update User Information

```sql
UPDATE users
SET email = 'newemail@example.com'
WHERE id = 1;
```

**Purpose:** Verify that existing user information is updated correctly.

---

## 7. Delete a User

```sql
DELETE FROM users
WHERE id = 1;
```

**Purpose:** Verify that the selected user record can be deleted.

---

## 8. Count Users

```sql
SELECT COUNT(*) FROM users;
```

**Purpose:** Verify the total number of user records.

---

## 9. Find Duplicate Emails

```sql
SELECT email, COUNT(*)
FROM users
GROUP BY email
HAVING COUNT(*) > 1;
```

**Purpose:** Identify duplicate email addresses.

---

## 10. Sort Users

```sql
SELECT * FROM users
ORDER BY name ASC;
```

**Purpose:** Verify that user records can be retrieved in alphabetical order.
