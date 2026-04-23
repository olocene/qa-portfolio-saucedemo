# Login Test Cases – SauceDemo

## TC-01 – Login with valid credentials

**Preconditions:**
- User is on login page https://www.saucedemo.com/

**Steps:**
1. Enter username: standard_user
2. Enter password: secret_sauce
3. Click Login

**Expected Result:**
- User is successfully logged in
- Redirect to inventory page

**Actual Result:**
- Login successful
- Unexpected popup displayed suggesting password change

**Status:** PASS (Bug identified)


---

## TC-02 – Login with invalid credentials

**Steps:**
1. Enter username: standard_user
2. Enter password: wrong_password
3. Click Login

**Expected Result:**
- Login denied
- Error message displayed

**Actual Result:**
- Login denied
- Correct error message displayed

**Status:** PASS


---

## TC-03 – Login with locked user

**Steps:**
1. Enter username: locked_out_user
2. Enter password: secret_sauce
3. Click Login

**Expected Result:**
- Login denied
- Message indicates user is locked

**Actual Result:**
- Login denied
- Correct message displayed

**Status:** PASS
