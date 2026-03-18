# Test Cases - Swag Labs

## Login Feature

**TC-01**  
**Technique:** Decision Table  
**Test Case ID:** LOGIN-01  
**Description:** Verify successful login with valid username  
**Pre-condition:** Browser open, on login page  
**Steps:**  
1. Enter username: standard_user || performance_glitch_user || visual_user
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
**Expected Result:** invalid login massage shows  
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
**Expected Result:** invalid login massage shows  
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
**Expected Result:** invalid login massage shows  
**Actual Result:**   
**Status:** [Pass/Fail]  
**Screenshot:** 
