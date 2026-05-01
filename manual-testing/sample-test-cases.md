
# Sample Test Cases – Login Functionality

The following test cases demonstrate my approach to validating
basic login functionality in a web application.

---

## ✅ Test Case 1: Valid Login

**Precondition:**  
User has a valid registered account.

**Steps:**
1. Navigate to the login page
2. Enter a valid username
3. Enter a valid password
4. Click the Login button

**Expected Result:**  
- User is successfully logged in
- User is redirected to the dashboard/home page

---

## ✅ Test Case 2: Invalid Password

**Precondition:**  
User has a valid registered account.

**Steps:**
1. Navigate to the login page
2. Enter a valid username
3. Enter an invalid password
4. Click the Login button

**Expected Result:**  
- Login fails
- An appropriate error message is displayed
- User remains on the login page

---

## ✅ Test Case 3: Empty Required Fields

**Steps:**
1. Navigate to the login page
2. Leave username and password fields empty
3. Click the Login button

**Expected Result:**  
- Validation message is displayed for required fields
- Login is not successful
