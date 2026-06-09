# Menu & Logout Test Cases - SauceDemo

## TC_061 - Verify Burger Menu Button Is Visible

**Priority:** High

**Precondition:** User is logged in.

**Steps:**

1. Navigate to the Inventory page.

**Expected Result:**

- Burger menu button is visible in the top-left corner.

---

## TC_062 - Verify Burger Menu Opens Successfully

**Priority:** High

**Precondition:** User is logged in.

**Steps:**

1. Click the Burger Menu button.

**Expected Result:**

- Side menu opens successfully.

---

## TC_063 - Verify All Menu Options Are Displayed

**Priority:** Medium

**Precondition:** Menu is open.

**Steps:**

1. Open the Burger Menu.

**Expected Result:**

- All Items
- About
- Logout
- Reset App State

options are displayed.

---

## TC_064 - Verify Menu Can Be Closed

**Priority:** Medium

**Precondition:** Menu is open.

**Steps:**

1. Click the Close (X) button.

**Expected Result:**

- Menu closes successfully.

---

## TC_065 - Verify Navigation Using "All Items"

**Priority:** Medium

**Precondition:** User is logged in.

**Steps:**

1. Open Burger Menu.
2. Click All Items.

**Expected Result:**

- User is redirected to the Inventory page.

---

## TC_066 - Verify About Link Navigation

**Priority:** Medium

**Precondition:** User is logged in.

**Steps:**

1. Open Burger Menu.
2. Click About.

**Expected Result:**

- User is redirected to the Sauce Labs website.

---

## TC_067 - Verify Logout Option Is Visible

**Priority:** High

**Precondition:** Menu is open.

**Steps:**

1. Open Burger Menu.

**Expected Result:**

- Logout option is displayed.

---

## TC_068 - Verify Successful Logout

**Priority:** High

**Precondition:** User is logged in.

**Steps:**

1. Open Burger Menu.
2. Click Logout.

**Expected Result:**

- User is logged out successfully.
- Login page is displayed.

---

## TC_069 - Verify User Cannot Access Inventory Page After Logout

**Priority:** High

**Precondition:** User has logged out.

**Steps:**

1. Logout successfully.
2. Attempt to access Inventory page URL directly.

**Expected Result:**

- Access is denied.
- User remains on Login page.

---

## TC_070 - Verify User Session Ends After Logout

**Priority:** High

**Precondition:** User has logged out.

**Steps:**

1. Logout successfully.
2. Click browser Back button.

**Expected Result:**

- User cannot access authenticated pages.

---

## TC_071 - Verify Logout from Cart Page

**Priority:** Medium

**Precondition:** User is on Cart page.

**Steps:**

1. Open Burger Menu.
2. Click Logout.

**Expected Result:**

- User is redirected to Login page.

---

## TC_072 - Verify Logout from Checkout Page

**Priority:** Medium

**Precondition:** User is on Checkout page.

**Steps:**

1. Open Burger Menu.
2. Click Logout.

**Expected Result:**

- User is logged out successfully.

---

## TC_073 - Verify Reset App State Option Is Visible

**Priority:** Medium

**Precondition:** Menu is open.

**Steps:**

1. Open Burger Menu.

**Expected Result:**

- Reset App State option is displayed.

---

## TC_074 - Verify Reset App State Clears Cart Data

**Priority:** Medium

**Precondition:** Product added to cart.

**Steps:**

1. Add product to cart.
2. Open Menu.
3. Click Reset App State.

**Expected Result:**

- Cart badge is cleared.
- Application state is reset.

---

## TC_075 - Verify Menu Remains Functional After Multiple Open/Close Actions

**Priority:** Low

**Precondition:** User is logged in.

**Steps:**

1. Open and close the menu multiple times.

**Expected Result:**

- Menu functions correctly without UI issues.
