# Cart Test Cases - SauceDemo

## TC_031 - Verify Add Single Product to Cart

**Priority:** High

**Precondition:** User is logged in and on the Inventory page.

**Steps:**

1. Click "Add to Cart" for any product.

**Expected Result:**

- Product is added to the cart.
- Cart badge count increases to 1.

---

## TC_032 - Verify Add Multiple Products to Cart

**Priority:** High

**Precondition:** User is logged in.

**Steps:**

1. Add multiple products to the cart.

**Expected Result:**

- All selected products are added successfully.
- Cart badge reflects the correct count.

---

## TC_033 - Verify Cart Badge Updates After Product Addition

**Priority:** Medium

**Precondition:** User is on Inventory page.

**Steps:**

1. Add a product to the cart.

**Expected Result:**

- Cart badge updates immediately with the correct quantity.

---

## TC_034 - Verify Remove Product from Inventory Page

**Priority:** High

**Precondition:** Product already added to cart.

**Steps:**

1. Click "Remove" for the product.

**Expected Result:**

- Product is removed from the cart.
- Cart badge count decreases accordingly.

---

## TC_035 - Verify Open Cart Page

**Priority:** High

**Precondition:** User is logged in.

**Steps:**

1. Click the cart icon.

**Expected Result:**

- User is redirected to the Cart page.

---

## TC_036 - Verify Added Product Appears in Cart

**Priority:** High

**Precondition:** Product added to cart.

**Steps:**

1. Open the Cart page.

**Expected Result:**

- Added product is displayed with correct details.

---

## TC_037 - Verify User Can Increase Quantity of the Same Product in Cart

**Priority:** Medium

**Test Type:** Functional / Negative

**Precondition:**

- User is logged in.
- At least one product is available on the Inventory page.

**Steps:**

1. Click "Add to Cart" for a product.
2. Attempt to add the same product again.
3. Open the Cart page.

**Expected Result:**

- User should be able to increase the quantity of the selected product.
- Cart should display the correct quantity count.
- Cart badge should reflect the updated quantity.

**Actual Result (Observed in SauceDemo):**

- The product can only be added once.
- No option is available to increase quantity.
- Cart quantity remains 1.

**Status:** Fail

## TC_038 - Verify Product Price Display in Cart

**Priority:** Medium

**Precondition:** Product exists in cart.

**Steps:**

1. Open Cart page.

**Expected Result:**

- Correct product price is displayed.

---

## TC_039 - Verify Remove Product from Cart Page

**Priority:** High

**Precondition:** Product exists in cart.

**Steps:**

1. Open Cart page.
2. Click Remove.

**Expected Result:**

- Product is removed from cart.

---

## TC_040 - Verify Continue Shopping Button

**Priority:** Medium

**Precondition:** User is on Cart page.

**Steps:**

1. Click Continue Shopping.

**Expected Result:**

- User is redirected to Inventory page.

---

## TC_041 - Verify Checkout Button Availability

**Priority:** High

**Precondition:** Cart contains at least one product.

**Steps:**

1. Open Cart page.

**Expected Result:**

- Checkout button is visible and enabled.

---

## TC_042 - Verify Checkout Navigation

**Priority:** High

**Precondition:** Cart contains products.

**Steps:**

1. Click Checkout.

**Expected Result:**

- User is redirected to Checkout Information page.

---

## TC_043 - Verify Cart Retains Products After Page Refresh

**Priority:** Medium

**Precondition:** Products added to cart.

**Steps:**

1. Refresh the Cart page.

**Expected Result:**

- Products remain in cart.

---

## TC_044 - Verify Cart Retains Products During Navigation

**Priority:** Medium

**Precondition:** Product added to cart.

**Steps:**

1. Navigate between Inventory and Cart pages.

**Expected Result:**

- Product remains in cart.

---

## TC_045 - Verify Empty Cart State

**Priority:** Medium

**Precondition:** No products in cart.

**Steps:**

1. Open Cart page.

**Expected Result:**

- Cart displays no products.
- No incorrect cart count is shown.
