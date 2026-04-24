# Test Cases - Practice Form

## Module: Automation Practice Form

---

### TC_001 - Submit form with all valid data

Priority: High

Precondition: User is on Practice Form page

Steps:

1. Enter valid First Name and Last Name
2. Enter valid Email
3. Select Gender
4. Enter valid Mobile Number (10 digits)
5. Select Date of Birth
6. Enter Subject
7. Select Hobbies
8. Upload a valid picture
9. Enter Address
10. Select State and City
11. Click Submit

Expected Result:
Form is submitted successfully and confirmation modal is displayed with correct data

---

### TC_002 - Submit form with empty required fields

Priority: High

Steps:

1. Click Submit without filling any fields

Expected Result:
Form should not be submitted and required fields should be highlighted

---

### TC_003 - Enter invalid email format

Priority: High

Steps:

1. Enter "abc" in Email field
2. Fill other required fields
3. Click Submit

Expected Result:
System should display validation error and prevent submission

---

### TC_004 - Enter mobile number with less than 10 digits

Priority: Medium

Steps:

1. Enter 5-digit mobile number
2. Fill other required fields
3. Click Submit

Expected Result:
System should reject invalid mobile number and prevent submission

---

### TC_005 - Verify Mobile Number accepts only defined length

Priority: High

Steps:

1. Enter a mobile number longer than 10 digits (e.g., 5511998366890)
2. Observe field behavior
3. Submit the form

Expected Result:
System should enforce defined length constraint (10 digits) and clearly restrict or validate extra input

---

### TC_006 - Enter mobile number with letters

Priority: Medium

Steps:

1. Enter "123abc4567" in Mobile Number field
2. Click Submit

Expected Result:
System should reject non-numeric characters and prevent submission

---

### TC_007 - Submit form without selecting Gender

Priority: Medium

Steps:

1. Fill all fields except Gender
2. Click Submit

Expected Result:
System should require Gender selection and prevent submission

---

### TC_008 - Select multiple hobbies

Priority: Low

Steps:

1. Select multiple hobby checkboxes
2. Submit form

Expected Result:
All selected hobbies should be displayed correctly in confirmation modal

---

### TC_009 - Verify valid image upload

Priority: Medium

Steps:

1. Upload a valid image file (.jpg or .png)
2. Fill required fields
3. Click Submit

Expected Result:
System should accept the image and display the file name correctly in confirmation modal

---

### TC_010 - Verify Picture Upload validation for file types

Priority: High

Steps:

1. Upload a non-image file (e.g., .pdf, .txt, .exe)
2. Click Submit

Expected Result:
System should reject invalid file formats and display validation message

---

### TC_011 - Select valid Date of Birth

Priority: Low

Steps:

1. Open date picker
2. Select a valid past date

Expected Result:
Selected date should be displayed correctly

---

### TC_012 - Validate future Date of Birth is not allowed

Priority: High

Steps:

1. Open date picker
2. Attempt to select a future date

Expected Result:
System should prevent selection or submission of future dates

---

### TC_013 - Enter invalid subject

Priority: Low

Steps:

1. Type random text in Subjects field

Expected Result:
System should not accept invalid subjects

---

### TC_014 - Select State and City

Priority: High

Steps:

1. Select a State
2. Select a City

Expected Result:
City options should update based on selected State

---

### TC_015 - Try selecting City before State

Priority: Medium

Steps:

1. Click City dropdown before selecting State

Expected Result:
City selection should be disabled until State is selected

---

### TC_016 - Verify confirmation modal Close button functionality

Priority: High

Steps:

1. Fill all required fields
2. Click Submit
3. Wait for confirmation modal
4. Click Close button

Expected Result:
Modal should close and user should return to the form

---
