# Bug Report – SauceDemo

## BUG-01: User Cannot Increase Quantity of the Same Product in Cart

**Bug ID:** BUG-01
**Module:** Cart
**Type:** Functional / Usability
**Severity:** Medium
**Priority:** Medium
**Environment:** Chrome (Latest Version), Windows 10

### Summary

The application does not provide a way to add multiple quantities of the same product to the cart. After adding a product once, the "Add to Cart" button changes to "Remove", preventing users from increasing the quantity.

### Preconditions

* User is logged in as `standard_user`.
* User is on the Products page.

### Steps to Reproduce

1. Log in to the SauceDemo application.
2. Select any product from the Products page.
3. Click **Add to Cart**.
4. Attempt to add the same product again.
5. Navigate to the Cart page.

### Expected Result

The user should be able to increase the quantity of a product in the cart, or the application should clearly indicate that only one quantity per product is supported.

### Actual Result

After adding a product once, the **Add to Cart** button changes to **Remove**. No option is available to increase quantity, and no message explains the limitation.

### Impact

Users may expect standard e-commerce functionality that allows purchasing multiple quantities of the same product. The current behavior may cause confusion and reduce usability.

### Status

Open

### Evidence

* Screenshot: To be attached
* Test Environment: SauceDemo Web Application
