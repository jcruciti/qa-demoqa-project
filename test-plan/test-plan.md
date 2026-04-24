# Test Plan - DemoQA Website

## Objective

Validate the main functionalities of the DemoQA website through manual testing, focusing on form behavior, input validation, and UI consistency.

---

## Scope

Website: https://demoqa.com

Modules to be tested:

* Forms (Automation Practice Form)

Features covered:

* Form submission
* Input field validation (Email, Mobile Number, Required Fields)
* File upload validation
* Date of Birth validation
* Dynamic dropdowns (State and City)
* Confirmation modal behavior

---

## Test Types

* Functional Testing
* Negative Testing
* UI Testing
* Input Validation Testing

---

## Test Data

Sample data used during testing includes:

* Valid and invalid email formats
* Mobile numbers with valid/invalid lengths and formats
* Image and non-image files for upload testing
* Valid and future dates for Date of Birth

---

## Tools

* Jira (Bug tracking)
* GitHub (Documentation)
* Browser (Chrome)
* Spreadsheet for test execution tracking

---

## Entry Criteria

* Website is accessible
* Test cases are created and reviewed
* Test data is prepared

---

## Exit Criteria

* All test cases executed
* All defects logged in Jira
* Test results documented in test execution report
* Critical defects identified and documented

---

## Risks & Assumptions

### Assumptions

* The application enforces standard validation rules for input fields
* File upload should accept only image formats (.jpg, .png, .jpeg)
* Mobile number field should follow a defined length constraint

### Risks

* DemoQA is a practice environment and may not enforce real-world validations
* Some behaviors may not represent production-level systems
* Lack of formal requirements may affect expected results interpretation

---

## Deliverables

* Test Plan
* Test Cases
* Test Execution Report
* Bug Reports
* Test Evidence (Screenshots)

---

## Test Execution Summary (based on current results)

* Total Test Cases: 16
* Passed: 11
* Failed: 5

### Key Defects Identified:

* Mobile number truncation (DQAT-3)
* File upload accepts invalid formats (DQAT-4)
* Future date of birth allowed (DQAT-5)
* Confirmation modal close button not working (DQAT-6)

---

## Conclusion

The application demonstrates basic functionality; however, several validation and UI issues were identified, particularly in input validation, file upload handling, and modal behavior.
