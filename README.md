
# Manual Test Case Suite: Loan Application Module

## Project Overview
This repository contains a comprehensive set of manual test cases for a **Loan Application Age Validation** feature. The goal is to ensure that only users within the eligible age range (26 to 50 inclusive) can successfully apply for a loan.

## Testing Techniques Applied
To ensure maximum coverage with the most efficient number of tests, I applied the following software testing design techniques:
* **Boundary Value Analysis (BVA):** Testing the exact edges of the age limits (25, 26, 50, 51).
* **Equivalence Partitioning (EP):** Grouping inputs into valid and invalid sets (Negative numbers, Strings, Valid range).
* **Error Guessing:** Testing extreme values (Age: 140) and empty fields.

## Test Case Summary
| Category | Test Inputs | Expected Result |
| :--- | :--- | :--- |
| **Valid Range** | 26, 35, 50 | Success / Loan Accepted |
| **Invalid Low** | 0 to 25, Negative numbers | Declined / Error Message |
| **Invalid High** | 51 and above | Declined / Error Message |
| **Invalid Data** | Characters (abc), Blank | Declined / Validation Error |

## Files in this Repository
* `Bank_TestCases.xlsx`: The main test case document containing steps, expected results, and execution status.
* `Bank_TestCases.pdf`: A non-editable version for quick viewing.

## Author
* **Barsha** - QA Tester / Manual Testing Portfolio
