# Computer Database – Manual Test Cases

## Overview
This repository contains **manual test cases** for the **Computer Database App**  
[Computer Database App](https://computer-database.gatling.io/computers)

The test cases ensure **end-to-end functionality**, covering both **positive and negative scenarios**, including security, validation, and UI behavior.

---

## Test Coverage
The test cases cover the following areas:
- **Functional Testing** (Add, Edit, Delete, Search)
- **Validation Testing** (Empty input, invalid data)
- **Security Testing** (SQL Injection, XSS)
- **UI & UX Behavior** (Cancel buttons, pagination, input validation)
- **Edge Cases & Performance Considerations**

---

## Test Case Format
Each test case follows this structured format:
- **Test Case ID** (Unique identifier)
- **Functionality** (Feature being tested)
- **Test Scenario** (What is being tested)
- **Preconditions** (Setup required before test execution)
- **Test Steps** (Step-by-step execution guide)
- **Test Data** (Input values, if applicable)
- **Expected Result** (Expected output for test success)
- **Severity** (Critical, High, Medium, Low)
- **Test Type** (Functional, Security, UI, Edge Case, etc.)

---

## How to Run the Tests
These are **manual test cases**. To execute them:
1. **Download** `Computer_Database_TestCases.csv`.
2. Open the **CSV file** using **Google Sheets, Excel, or any spreadsheet tool**.
3. Follow the **Test Steps** provided for each test scenario.
4. Perform the steps on the **Computer Database App**.
5. Compare actual vs. expected results.
6. Mark **Pass/Fail** accordingly in your own test execution document.

---

## Repository Structure
```
/computer-database-manual-tests/
│
├── Computer_Database_TestCases.csv  # Test cases in CSV format
├── README.md                        # This document
```

---

## Author
QA Engineer – [Nitu Kumari]
