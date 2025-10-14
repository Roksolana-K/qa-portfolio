# ✅ Checklist – JPetStore Cart Feature

---

## 🧩 General Requirements

| #  | Checklist Item                                                       | Priority  | Result     | Bug ID   | Comment                                               |
|----|----------------------------------------------------------------------|------------|-------------|----------|-----------------------------------------------------|
| 1  | Cart is accessible from any page                                     | High       | ❌ Failed   | PS-001   | Not accessible from “FAQ” page                      |
| 2  | Cart icon has tooltip “Cart”                                         | Low        | ❌ Failed   | PS-002   | Tooltip missing                                     |
| 3  | When a product is added, all info about it is shown in a table with columns: Item ID, Product ID, Name, Description, In Stock?, Quantity, List Price, Total Cost   | Medium     | ❌ Failed   | PS-003   | Missing “Name” column                               |
| 4  | The last row contains info about the total price of added products and is named: "Sub Total" and has a button "Update Cart" (updates all products in Cart)                     | High       | ✅ Passed   |       |                                                     |
| 5  | Cart by default is empty and has text "Your cart is empty"                           | Medium     | ✅ Passed   |         |                                                     |
| 6  | If at least one product is added, button "Proceed to Checkout” should be present under the table                     | Medium     | ✅ Passed   |        |                                                     |
| 7  | Button "Proceed to Checkout” is not shown when the Cart is empty                      | Low        | ✅ Passed   |         |                                                     |
| 8  | User is logged in: click on button "Proceed to Checkout” redirects to Checkout page                          | Critical   | ✅ Passed   |        |                                                     |
| 9  | User is not logged in: click on button "Proceed to Checkout” redirects to login page                                       | Medium     | ✅ Passed   |        |                                                     |
| 10 | Click on “Return to Main Menu” link should take the user to another page                       | Low        | ✅ Passed   |        |                                                     |


---

## 🧱 Adding and Removing Products

| #  | Checklist Item                                                       | Priority  | Result     | Bug ID   | Comment                                               |
|---|-----------------------------------------------------------------------|-----------|---------   |--------  |----------|
| 11 | Click on “Add to Cart” button from PDP adds the product to the cart | Medium    | ✅ Passed  |          |          |
| 12 | Click on “Add to Cart” button from the list of products adds the product to the cart                                        | Medium    | ✅ Passed  |          |          |
| 13 | If at least 1 product in the cart: it should be displayed as a badge with a quantity of added to the Cart products on the Cart’s icon                              | Low       | ❌ Failed  | PS-004   | No badge displayed |
| 14 | If no products in the Cart: badge is not displayed. Only Cart icon.                                             | Low       | ✅ Passed  |          |          |
| 15 | When cart is not empty the column "Item ID" should have clickable links                                    | Low       | ✅ Passed  |          |          |
| 16 | When cart is not empty the column "Name" should have clickable links                                       | Low       | ⚪ Skipped |          | Not implemented |
| 17 | "Quantity" field in the Cart should accept numbers                                | Medium    | ✅ Passed  |          |          |
| 18 | "Quantity" field in the Cart should not accept upper and lower case letters                                          | Medium    | ✅ Passed  |          |          |
| 19 | "Quantity" field in the Cart should not accept special symbols                                           | Medium    | ✅ Passed  |          |          |
| 20 | "Quantity" field in the Cart should not accept decimals                                        | Medium    | ✅ Passed  |          |          |
| 21 | "Quantity" field in the Cart should not accept negative numbers                                | Medium    | ❌ Failed  | PS-005   | Field accepts negative number (clears cart) |
| 22 | User should be able to add 5 items of the same product                                   | Critical  | ✅ Passed  |          |          |
| 23 | User should not be able to add more than 5 items of the same product                               | Medium    | ❌ Failed  | PS-006   | No restriction |
| 24 | Quantity validation occurs when entered a new quantity and pressed Enter or clicked on the “Update Cart” button                             | Medium    | ✅ Passed  |          |          |
| 25 | Attempt to add more than 5 products to cart: under the table appears validation message "We are sorry, but you can’t buy more than 5 items of the product."                             | Low       | ❌ Failed  | PS-007   | No error message shown |
| 26 | If product is not available or there is not enough: under the table appears message: "We are sorry, but we have only N items of this product for now. Would you like to subscribe to notifications when this product will be available?"                      | Low       | ❌ Failed  | PS-008   | Message missing |
| 27 | Click on "Remove" button near product price: removes product from Cart                                      | High      | ✅ Passed  |          |          |
| 28 | Enter "Quantity" = 0 and update the Cart: product is removed from Cart                                     | Medium    | ✅ Passed  |          |          |
| 29 | Product is not in stock: user is not able to add it to Cart                              | Critical  | ❌ Failed  | PS-009   | Out-of-stock item can be added |

---

## 🔁 Cross-Session Cart Feature

| # | Checklist Item | Priority | Result | Bug ID | Comment |
|---|----------------|-----------|---------|--------|----------|
| 30 | Logged-in user: adds product to Cart -> it should be displayed in all sessions | High | ❌ Failed | PS-010 | No synchronization |
| 31 | Logged-in user: adds product to Cart and logs out -> Cart is empty for this session | Critical | ✅ Passed |  |  |
| 32 | Logged-in user: adds product to Cart, logs out and logs in again -> Cart stays the same as it was before logout. All products in place. | High | ❌ Failed | PS-011 | Cart resets after re-login |
| 33 | Logged-in user, cart with products: if product removed from Cart -> it is removed from all other sessions too | Medium | ❌ Failed | PS-012 | Product remains in 2nd browser |

---

## 📊 Summary

| Total tests | Passed | Failed | Skipped |
|------------------|--------|--------|----------|
| 33 | 20 | 12 | 1 |

> **12 bugs found:** 5 Critical, 2 Major, 3 Moderate, and 2 Minor  
> See detailed reports in `bug_reports.md`.

---

## 💬 Notes
- Test execution was done manually based on course requirements.  
- Checklist created manually by Roksolana K. as part of QA portfolio.
