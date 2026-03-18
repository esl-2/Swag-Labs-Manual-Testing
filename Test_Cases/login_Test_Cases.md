# Test Cases - Swag Labs

## Login Feature

**TC-01**  
**Technique:** Decision Table  
**Test Case ID:** LOGIN-01  
**Description:** Verify successful login with valid username  
**Pre-condition:** Browser open, on login page  
**Steps:**  
1. Enter username: standard_user 
2. Enter password: secret_sauce  
3. Click Login  
**Expected Result:** Redirect to Products page + "Swag Labs" title visible  
**Actual Result:**   
**Status:** [Pass/Fail]  
**Screenshot:** 

**TC-02**  
**Technique:** Decision Table  
**Test Case ID:** LOGIN-02 
**Description:** Verify wrong login with invalid username  
**Pre-condition:** Browser open, on login page  
**Steps:**  
1. Enter username: Dom44
2. Enter password: secret_sauce  
3. Click Login  
**Expected Result:** invalid username massage shows  
**Actual Result:**   
**Status:** [Pass/Fail]  
**Screenshot:** 

**TC-03**  
**Technique:** Decision Table  
**Test Case ID:** LOGIN-03
**Description:** Verify wrong login without typing username  
**Pre-condition:** Browser open, on login page  
**Steps:**  
1. Enter username: 
2. Enter password: secret_sauce  
3. Click Login  
**Expected Result:** invalid username massage shows  
**Actual Result:**   
**Status:** [Pass/Fail]  
**Screenshot:** 

**TC-04**  
**Technique:** Decision Table  
**Test Case ID:** LOGIN-04
**Description:** Verify wrong login with invalid password  
**Pre-condition:** Browser open, on login page  
**Steps:**  
1. Enter username: standard_user
2. Enter password: not_secret_sauce  
3. Click Login  
**Expected Result:** invalid password massage shows  
**Actual Result:**   
**Status:** [Pass/Fail]  
**Screenshot:** 

**TC-05**  
**Technique:** Decision Table  
**Test Case ID:** LOGIN-05
**Description:** Verify wrong login with locked_out_user  
**Pre-condition:** Browser open, on login page  
**Steps:**  
1. Enter username: locked_out_user
2. Enter password: secret_sauce  
3. Click Login  
**Expected Result:** locked out user massage   
**Actual Result:**   
**Status:** [Pass/Fail]  
**Screenshot:** 
