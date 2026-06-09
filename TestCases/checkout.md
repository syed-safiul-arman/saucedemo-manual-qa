# Checkout Test Cases - SauceDemo

## TC_046 - Verify Navigation to Checkout Information Page

**Priority:** High

**Precondition:** User has at least one product in the cart.

**Steps:**

1. Open Cart page.
2. Click Checkout.

**Expected Result:**

* User is redirected to the Checkout Information page.

---

## TC_047 - Verify Checkout Information Page Elements

**Priority:** Medium

**Precondition:** User is on Checkout Information page.

**Steps:**

1. Observe page fields and buttons.

**Expected Result:**

* First Name, Last Name, and Postal Code fields are displayed.
* Continue and Cancel buttons are available.

---

## TC_048 - Verify Successful Checkout with Valid Information

**Priority:** High

**Precondition:** User is on Checkout Information page.

**Steps:**

1. Enter valid First Name.
2. Enter valid Last Name.
3. Enter valid Postal Code.
4. Click Continue.

**Expected Result:**

* User proceeds to Checkout Overview page.

---

## TC_049 - Verify Checkout with Empty First Name

**Priority:** High

**Steps:**

1. Leave First Name empty.
2. Enter Last Name and Postal Code.
3. Click Continue.

**Expected Result:**

* Validation error message is displayed.

---

## TC_050 - Verify Checkout with Empty Last Name

**Priority:** High

**Steps:**

1. Enter First Name.
2. Leave Last Name empty.
3. Enter Postal Code.
4. Click Continue.

**Expected Result:**

* Validation error message is displayed.

---

## TC_051 - Verify Checkout with Empty Postal Code

**Priority:** High

**Steps:**

1. Enter First Name.
2. Enter Last Name.
3. Leave Postal Code empty.
4. Click Continue.

**Expected Result:**

* Validation error message is displayed.

---

## TC_052 - Verify Checkout with All Fields Empty

**Priority:** High

**Steps:**

1. Leave all fields blank.
2. Click Continue.

**Expected Result:**

* Appropriate validation message is displayed.

---

## TC_053 - Verify Cancel Button on Checkout Information Page

**Priority:** Medium

**Steps:**

1. Click Cancel.

**Expected Result:**

* User returns to Cart page.

---

## TC_054 - Verify Product Details on Checkout Overview Page

**Priority:** High

**Precondition:** User has completed checkout information.

**Steps:**

1. Open Checkout Overview page.

**Expected Result:**

* Product name, description, quantity, and price are displayed correctly.

---

## TC_055 - Verify Payment Information Display

**Priority:** Medium

**Steps:**

1. Open Checkout Overview page.

**Expected Result:**

* Payment information section is displayed.

---

## TC_056 - Verify Shipping Information Display

**Priority:** Medium

**Steps:**

1. Open Checkout Overview page.

**Expected Result:**

* Shipping information section is displayed.

---

## TC_057 - Verify Item Total Calculation

**Priority:** High

**Steps:**

1. Add products to cart.
2. Proceed to Checkout Overview.

**Expected Result:**

* Item total equals the sum of selected product prices.

---

## TC_058 - Verify Total Price Calculation

**Priority:** High

**Steps:**

1. Proceed to Checkout Overview.

**Expected Result:**

* Total price equals Item Total + Tax.

---

## TC_059 - Verify Finish Checkout Process

**Priority:** High

**Steps:**

1. Complete checkout information.
2. Click Finish.

**Expected Result:**

* Order is completed successfully.
* Confirmation page is displayed.

---

## TC_060 - Verify Checkout Completion Message

**Priority:** Medium

**Precondition:** Checkout completed successfully.

**Steps:**

1. Observe confirmation page.

**Expected Result:**

* Success message is displayed.
* User receives order completion confirmation.
