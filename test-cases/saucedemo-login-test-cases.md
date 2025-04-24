# Saucedemo Login Page - Manual Test Cases

## Test Case 1: Login with valid credentials
- **Steps**:
  1. Go to https://www.saucedemo.com
  2. Enter username: standard_user
  3. Enter password: secret_sauce
  4. Click Login
- **Expected Result**: Redirected to inventory page
- **Status**: Pass

## Test Case 2: Login with invalid password
- **Steps**:
  1. Enter username: standard_user
  2. Enter password: wrong_password
  3. Click Login
- **Expected Result**: Error message: "Username and password do not match..."
- **Status**: Pass

## Test Case 3: Login with empty fields
- **Steps**:
  1. Open login page
  2. Click Login without entering username or password
- **Expected Result**: Error message: "Username is required"
- **Status**: Pass

## Test Case 4: Login with locked out user
- **Steps**:
  1. Enter username: locked_out_user
  2. Enter password: secret_sauce
  3. Click Login
- **Expected Result**: Error message: "Sorry, this user has been locked out."
- **Status**: Pass

## Test Case 5: Special characters in username
- **Steps**:
  1. Enter username: !@#$%^&*()
  2. Enter password: secret_sauce
  3. Click Login
- **Expected Result**: Error message or rejection
- **Status**: Pass
