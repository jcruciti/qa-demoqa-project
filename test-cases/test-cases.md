# Test Cases - DemoQA

## Module: Practice Form

### TC_001 - Submit form with valid data
Precondition: User is on Practice Form page

Steps:
1. Enter First Name
2. Enter Last Name
3. Enter valid Email
4. Select Gender
5. Enter Mobile Number
6. Click Submit

Expected Result:
Form is submitted successfully and confirmation modal is displayed

---

### TC_002 - Submit form with empty required fields

Steps:
1. Click Submit without filling fields

Expected Result:
Form should not be submitted and validation messages should appear

---

### TC_003 - Enter invalid email

Steps:
1. Enter "abc" in Email field
2. Fill other required fields
3. Click Submit

Expected Result:
System should show email validation error

---

## Module: Text Box

### TC_004 - Submit text box with valid data

Steps:
1. Enter Full Name
2. Enter Email
3. Enter Current Address
4. Enter Permanent Address
5. Click Submit

Expected Result:
Entered data should be displayed below

---

### TC_005 - Submit text box with invalid email

Steps:
1. Enter invalid email
2. Click Submit

Expected Result:
Email field should show validation error
