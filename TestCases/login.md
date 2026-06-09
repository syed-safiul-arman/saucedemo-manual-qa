# Login Test Cases - SauceDemo

## TC_001 - Verify Login with Valid Credentials

**Priority:** High

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter username `standard_user`.
2. Enter password `secret_sauce`.
3. Click the **Login** button.

**Expected Result:**

* User is successfully authenticated.
* User is redirected to the Inventory page.
* Product inventory is displayed without errors.

---

## TC_002 - Verify Login with Invalid Password

**Priority:** High

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter username `standard_user`.
2. Enter an invalid password.
3. Click the **Login** button.

**Expected Result:**

* Login attempt is rejected.
* Appropriate error message is displayed.
* User remains on the login page.

---

## TC_003 - Verify Login with Invalid Username

**Priority:** High

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter an invalid username.
2. Enter password `secret_sauce`.
3. Click the **Login** button.

**Expected Result:**

* Login attempt fails.
* Error message is displayed.
* User remains on the login page.

---

## TC_004 - Verify Login with Invalid Username and Invalid Password

**Priority:** High

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter an invalid username.
2. Enter an invalid password.
3. Click the **Login** button.

**Expected Result:**

* Login is not successful.
* Appropriate error message is displayed.
* User remains on the login page.

---

## TC_005 - Verify Login with Empty Username and Password

**Priority:** High

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Leave the Username field blank.
2. Leave the Password field blank.
3. Click the **Login** button.

**Expected Result:**

* Login is prevented.
* Validation message indicating that the username is required is displayed.
* User remains on the login page.

---

## TC_006 - Verify Login with Empty Username

**Priority:** Medium

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Leave the Username field blank.
2. Enter password `secret_sauce`.
3. Click the **Login** button.

**Expected Result:**

* Login is prevented.
* Username required validation message is displayed.
* User remains on the login page.

---

## TC_007 - Verify Login with Empty Password

**Priority:** Medium

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter username `standard_user`.
2. Leave the Password field blank.
3. Click the **Login** button.

**Expected Result:**

* Login is prevented.
* Password required validation message is displayed.
* User remains on the login page.

---

## TC_008 - Verify Login with Locked-Out User Account

**Priority:** High

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter username `locked_out_user`.
2. Enter password `secret_sauce`.
3. Click the **Login** button.

**Expected Result:**

* Login attempt is blocked.
* Locked-out user error message is displayed.
* User remains on the login page.

---

## TC_009 - Verify Username Field Accepts User Input

**Priority:** Low

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Click inside the Username field.
2. Enter any valid text.

**Expected Result:**

* Entered text is displayed in the Username field.
* Field remains editable and responsive.

---

## TC_010 - Verify Password Field Masks Entered Characters

**Priority:** Medium

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Click inside the Password field.
2. Enter any password value.

**Expected Result:**

* Password characters are masked.
* Actual password text is not visible to the user.

---

## TC_011 - Verify Login Using the Enter Key

**Priority:** Medium

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter username `standard_user`.
2. Enter password `secret_sauce`.
3. Press the **Enter** key instead of clicking Login.

**Expected Result:**

* Login request is submitted successfully.
* User is redirected to the Inventory page.

---

## TC_012 - Verify Error Message Is Cleared After Successful Login

**Priority:** Medium

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Attempt login using invalid credentials.
2. Verify that an error message is displayed.
3. Enter valid credentials.
4. Click the **Login** button.

**Expected Result:**

* User logs in successfully.
* Previously displayed error message is no longer visible.
* Inventory page is displayed.

---

## TC_013 - Verify Login with Leading and Trailing Spaces in Username

**Priority:** Medium

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter username with leading and trailing spaces (e.g., `standard_user`).
2. Enter password `secret_sauce`.
3. Click the **Login** button.

**Expected Result:**

* Application handles the input as per expected behavior.
* No application crash or unexpected error occurs.
* Login result is consistent with the application's validation rules.

---

## TC_014 - Verify Copy and Paste Functionality in Username Field

**Priority:** Low

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Copy a valid username value.
2. Paste the value into the Username field.

**Expected Result:**

* Username is pasted successfully.
* Field accepts pasted content without issues.
* User can proceed with login normally.

---

## TC_015 - Verify Successful Login Redirects User to Inventory Page

**Priority:** High

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter valid credentials.
2. Click the **Login** button.

**Expected Result:**

* User is successfully authenticated.
* User is redirected to the Inventory page.
* Product inventory loads correctly and is available for interaction.
