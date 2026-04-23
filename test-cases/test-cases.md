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

### TC_003 - Submit form without First Name
Priority: High  

Steps:
1. Fill all fields except First Name  
2. Click Submit  

Expected Result:
Form should not be submitted and First Name should be required  

---

### TC_004 - Enter invalid email format
Priority: High  

Steps:
1. Enter "abc" in Email field  
2. Fill other required fields  
3. Click Submit  

Expected Result:
System should show validation error for invalid email  

---

### TC_005 - Enter mobile number with less than 10 digits
Priority: Medium  

Steps:
1. Enter 5-digit mobile number  
2. Fill other required fields  
3. Click Submit  

Expected Result:
System should show validation error  

---

### TC_006 - Enter mobile number with letters
Priority: Medium  

Steps:
1. Enter "12345abcde" in Mobile Number  
2. Click Submit  

Expected Result:
Field should not accept letters or should show validation error  

---

### TC_007 - Submit form without selecting Gender
Priority: Medium  

Steps:
1. Fill all fields except Gender  
2. Click Submit  

Expected Result:
Form behavior should be validated (should require gender or allow submission)  

---

### TC_008 - Select multiple hobbies
Priority: Low  

Steps:
1. Select multiple hobby checkboxes  
2. Submit form  

Expected Result:
All selected hobbies should be displayed correctly in confirmation  

---

### TC_009 - Upload valid image file
Priority: Medium  

Steps:
1. Upload an image file (e.g., .jpg or .png)  
2. Submit form  

Expected Result:
File should be uploaded successfully  

---

### TC_010 - Attempt to upload invalid file format
Priority: Low  

Steps:
1. Try uploading unsupported file format (if possible)  

Expected Result:
System should restrict or handle invalid file type  

---

### TC_011 - Select date of birth
Priority: Low  

Steps:
1. Open Date Picker  
2. Select a valid date  

Expected Result:
Selected date should be displayed correctly  

---

### TC_012 - Enter subject using autocomplete
Priority: Low  

Steps:
1. Type "Math" in Subjects field  
2. Select suggestion  

Expected Result:
Subject should be added successfully  

---

### TC_013 - Enter invalid subject
Priority: Low  

Steps:
1. Type random text in Subjects field  

Expected Result:
System should restrict invalid entries or not add subject  

---

### TC_014 - Select State and City
Priority: High  

Steps:
1. Select a State  
2. Select a City  

Expected Result:
City options should depend on selected State  

---

### TC_015 - Try selecting City before State
Priority: Medium  

Steps:
1. Click City dropdown before selecting State  

Expected Result:
City selection should be disabled or show no options  

---
