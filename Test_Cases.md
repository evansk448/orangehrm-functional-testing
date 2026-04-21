# Test Cases

## TC-01: Valid Login

**Steps:**
1. Open login page
2. Enter valid username and password
3. Click Login

**Expected Result:**
User is authenticated and redirected to dashboard.

---

## TC-02: Invalid Login

**Steps:**
1. Enter invalid credentials
2. Click Login

**Expected Result:**
Login fails and error message is displayed.

---

## TC-03: Required Field Validation (Login)

**Steps:**
1. Leave username and password blank
2. Click Login

**Expected Result:**
Required field validation messages are displayed.

---

## TC-04: Forgot Password Navigation

**Steps:**
1. Click “Forgot your password?”

**Expected Result:**
User is redirected to password reset page.

---

## TC-05: Candidate Search (Recruitment)

**Steps:**
1. Navigate to Recruitment module
2. Enter search criteria
3. Click Search

**Expected Result:**
Matching candidates are displayed.

---

## TC-06: No Results Search

**Steps:**
1. Enter criteria with no matching records (e.g., Vacancies - Job Title: ‘Chief Executive Officer’, Status: ‘Active’)
2. Click Search

**Expected Result:**
System displays “No Records Found” or empty results.

---

## TC-07: Employee Search by Name

**Steps:**
1. Navigate to Directory
2. Enter employee name
3. Click Search

**Expected Result:**
Matching employee records are returned.

---

## TC-08: Add Employee (Valid Data)

**Steps:**
1. Navigate to PIM module
2. Click Add Employee
3. Enter required fields
4. Save

**Expected Result:**
Employee record is created successfully.

---

## TC-09: Add Employee (Missing Required Fields)

**Steps:**
1. Leave required fields blank
2. Click Save

**Expected Result:**
Validation messages are displayed and record is not created.

---

## TC-10: Punch In / Punch Out

**Steps:**
1. Navigate to Time module
2. Punch in
3. Punch out

**Expected Result:**
System records accurate timestamps.
