# SQL Test Execution Report

## Project

SQL Database Testing

## Objective

To execute SQL test cases and verify the accuracy, integrity, and correctness of data stored in the database.

## Test Environment

| Item | Details |
|---|---|
| Database | MySQL |
| Database Tool | phpMyAdmin |
| Testing Type | Database Testing |
| Tester | Priyanka Rouniyar |

## Test Execution Summary

| Test Case ID | Test Scenario | Status |
|---|---|---|
| SQL-TC-001 | Verify user records | PASS |
| SQL-TC-002 | Verify specific user data | PASS |
| SQL-TC-003 | Verify updated user data | PASS |
| SQL-TC-004 | Verify deleted user record | PASS |
| SQL-TC-005 | Check duplicate emails | PASS |

## Execution Summary

**Total Test Cases:** 5  
**Executed:** 5  
**Passed:** 5  
**Failed:** 0  
**Not Executed:** 0

## Overall Result

**PASS**

All five SQL test cases were executed successfully using MySQL and phpMyAdmin.

---

## Executed SQL Queries

### SQL-TC-001 – Verify User Records

```sql
SELECT * FROM users;
