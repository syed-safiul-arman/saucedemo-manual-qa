# Test Plan – SauceDemo (Manual Web Testing)

## 1. Overview

This test plan explains the manual testing activities performed on the SauceDemo website. The main goal is to check whether the core features of the application work as expected from a user's point of view. The testing focuses on login, browsing products, managing the shopping cart, and completing the checkout process.

## 2. Objectives

The objectives of this testing are:

* To verify that the main user flows work correctly.
* To check how the application behaves with both valid and invalid inputs.
* To identify any functional issues or user interface problems.
* To create clear QA documentation, including test cases, bug reports, and test results.
* To build a practical manual testing project for learning and portfolio purposes.

## 3. Scope

### In Scope

The following features will be tested:

* User login functionality
* Product inventory page
* Product sorting options
* Product details and information
* Add to cart and remove from cart functionality
* Shopping cart page
* Checkout process
* Logout functionality

### Out of Scope

The following areas are not included in this testing effort:

* Performance testing
* Security testing
* API testing
* Mobile responsiveness testing
* Automation testing
* Cross-browser compatibility testing

## 4. Test Types

The following testing types will be performed:

* **Smoke Testing** – To ensure the main features are working before detailed testing begins.
* **Functional Testing** – To verify that each feature works according to requirements.
* **Positive Testing** – To confirm the system behaves correctly with valid inputs.
* **Negative Testing** – To check how the system handles invalid inputs and error scenarios.
* **UI Validation** – To verify that buttons, labels, messages, and page layouts appear correctly.
* **Exploratory Testing** – To discover unexpected issues by interacting with the application freely.

## 5. Test Environment

| Item                | Details                        |
| ------------------- | ------------------------------ |
| Application         | https://www.saucedemo.com      |
| Browser             | Google Chrome (Latest Version) |
| Operating System    | Windows 10/11                  |
| Testing Method      | Manual Testing                 |
| Evidence Collection | Screenshots                    |

## 6. Entry Criteria

Testing can begin when:

* The SauceDemo website is accessible.
* Test user accounts are available.
* Test cases have been prepared.
* The required browser and testing tools are ready.

## 7. Exit Criteria

Testing will be considered complete when:

* All planned test cases have been executed.
* Any defects found have been documented.
* The critical user flow (Login → Add Product to Cart → Checkout) works successfully.
* Test execution results have been recorded.
* The test summary report has been completed.

## 8. Risks & Mitigation

| Risk                                                    | Mitigation                                         |
| ------------------------------------------------------- | -------------------------------------------------- |
| Application data may reset during testing               | Repeat the required setup steps if needed          |
| Public test accounts may become temporarily unavailable | Retry testing using another available test account |
| Browser-related differences may affect results          | Perform all testing using Google Chrome            |

## 9. Deliverables

The following documents and evidence will be produced:

* Test Plan
* Test Cases
* Bug Reports
* Test Execution Report
* Test Summary Report
* Screenshots and Testing Evidence
* README Documentation for the project repository
