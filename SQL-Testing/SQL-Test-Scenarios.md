# SQL Test Scenarios

## 1. Data Retrieval Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| SQL-TS-001 | Retrieve all user records | All available user records should be displayed |
| SQL-TS-002 | Retrieve a user using ID | Correct user record should be displayed |
| SQL-TS-003 | Retrieve a user using email | Correct user record should be displayed |
| SQL-TS-004 | Retrieve specific columns | Only requested columns should be displayed |

## 2. Data Modification Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| SQL-TS-005 | Insert a new user record | New user should be stored correctly |
| SQL-TS-006 | Update existing user information | Updated information should be stored correctly |
| SQL-TS-007 | Delete an existing user | User record should be removed |
| SQL-TS-008 | Verify data after update | Updated values should match expected values |
| SQL-TS-009 | Verify data after deletion | Deleted record should no longer exist |

## 3. Data Validation Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| SQL-TS-010 | Count total user records | Correct number of records should be returned |
| SQL-TS-011 | Check duplicate email addresses | Duplicate email addresses should be identified |
| SQL-TS-012 | Verify user information | Stored data should match expected data |
| SQL-TS-013 | Verify required fields | Required fields should contain valid data |

## 4. Negative Testing Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| SQL-TS-014 | Search for a non-existing user | No matching record should be returned |
| SQL-TS-015 | Search using an invalid ID | No matching record should be returned |
| SQL-TS-016 | Check duplicate data | Duplicate records should be detected |

## Testing Approach

The SQL testing scenarios cover:

- Data retrieval
- Data insertion
- Data updates
- Data deletion
- Data validation
- Duplicate data detection
- Positive testing
- Negative testing

## Tools Used

- MySQL
- phpMyAdmin
- SQL

## Status

**Completed**
