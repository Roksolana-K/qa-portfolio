# 🧾 Bug Reports    


## 🐞 PS-001 - Cart is not accessible from "FAQ" page

| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-001 |
| **Summary** |  | Cart is not accessible from "FAQ" page |
| **Bug details** | **Preconditions** | Open main page of [JPetStore](https://jpetstore.mate.academy/actions/Catalog.action) |
|  | **Steps to reproduce** | 1. Click on "?" button on header |
|  | **Actual result** | Cart is not visible and available |
|  | **Expected result** | Cart is accessible from all pages |
|  | **Attachments** | Screenshot: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-001.png) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Moderate |

---

## 🐞 PS-002 - Cart has no tooltip

| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-002 |
| **Summary** |  | Cart has no tooltip |
| **Bug details** | **Preconditions** | Open main page of [JPetStore](https://jpetstore.mate.academy/actions/Catalog.action) |
|  | **Steps to reproduce** | 1. Hover over the Cart icon |
|  | **Actual result** | No tooltip is shown |
|  | **Expected result** | Cart icon should have tooltip |
|  | **Attachments** | Screenshot: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-002.png) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Minor |

---

## 🐞 PS-003 - [Shopping Cart table]: missing "Name" column

| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-003 |
| **Summary** |  | [Shopping Cart table]: has no "Name" column |
| **Bug details** | **Preconditions** | Cart should not be empty |
|  | **Steps to reproduce** | 1. Go to [Main Page](https://jpetstore.mate.academy/actions/Catalog.action)<br>2. Add a product to the Cart<br>3. Observe "Shopping Cart" table |
|  | **Actual result** | "Shopping Cart" table doesn't have "Name" column |
|  | **Expected result** | "Shopping Cart" table should have columns: *Item ID, Product ID, Name, Description, In Stock?, Quantity, List Price, Total Cost* |
|  | **Attachments** | Screenshot: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-003.png) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Moderate |

---

## 🐞 PS-004 - [Cart icon]: badge with product amount not displayed

| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-004 |
| **Summary** |  | [Cart icon]: badge with amount of products not displayed |
| **Bug details** | **Preconditions** | Cart should not be empty |
|  | **Steps to reproduce** | 1. Go to [Main Page](https://jpetstore.mate.academy/actions/Catalog.action)<br>2. Add a product to the Cart<br>3. Observe Cart icon |
|  | **Actual result** | Cart icon has no badge with product count |
|  | **Expected result** | A badge showing the product count should be displayed on the Cart icon |
|  | **Attachments** | Screenshot: [link_1](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-004.1.png), [link_2](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-004.2.png) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Minor |

---

## 🐞 PS-005 - [Shopping Cart]: "Quantity" field accepts negative numbers

| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-005 |
| **Summary** |  | [Shopping Cart]: "Quantity" field accepts negative number |
| **Bug details** | **Preconditions** | Cart should not be empty |
|  | **Steps to reproduce** | 1. Go to [Main Page](https://jpetstore.mate.academy/actions/Catalog.action)<br>2. Add a product to the Cart<br>3. Enter a negative number in "Quantity"<br>4. Click "Update Cart" |
|  | **Actual result** | Product disappears from the Cart |
|  | **Expected result** | Product should remain, "Quantity" field should reset to its previous value |
|  | **Attachments** | Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-005.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Critical |

---

## 🐞 PS-006 - User can add more than 5 items of the same product

| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-006 |
| **Summary** |  | User can add more than 5 items of the same product |
| **Bug details** | **Preconditions** | Cart is not empty |
|  | **Steps to reproduce** | 1. Go to [Main Page](https://jpetstore.mate.academy/actions/Catalog.action)<br>2. Add a product to the Cart<br>3. Set "Quantity" to a number bigger than 5<br>4. Click "Update Cart" |
|  | **Actual result** | Quantity is accepted, no validation or error message |
|  | **Expected result** | User should not be able to add more than 5 items of the same product |
|  | **Attachments** | Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-006.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Critical |

---

## 🐞 PS-007 - No validation error when adding >5 items
| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-007 |
| **Summary** |  | No validation error message when adding more than 5 items of same product |
| **Bug details** | **Preconditions** | Cart is not empty |
|  | **Steps to reproduce** | 1. Go to [Main Page](https://jpetstore.mate.academy/actions/Catalog.action)<br>2. Add a product<br>3. Change "Quantity" > 5<br>4. Click "Update Cart" |
|  | **Actual result** | No validation or warning message appears |
|  | **Expected result** | Message “We are sorry, but you can’t buy more than 5 items of this product.” should appear |
|  | **Attachments** | Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-007.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Moderate |

---

## 🐞 PS-008 - No error when adding out-of-stock product
| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-008 |
| **Summary** |  | No error message when adding out-of-stock product |
| **Bug details** | **Preconditions** | — |
|  | **Steps to reproduce** | 1. Open [Main Page](https://jpetstore.mate.academy/actions/Catalog.action)<br>2. Add a product to Cart<br>3. Observe "In Stock" column |
|  | **Actual result** | Product not in stock but no error message shown |
|  | **Expected result** | "We are sorry, but we have only N items of this product for now. Would you like to subscribe to notifications when this product will be available?" message should appear when user adds to the Cart a product that is not available. |
|  | **Attachments** | Screenshot: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-008.1.png), Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-008.2.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Major |

---

## 🐞 PS-009 - Possible to add out-of-stock product
| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-009 |
| **Summary** |  | It is possible to add out-of-stock product to Cart |
| **Bug details** | **Preconditions** | — |
|  | **Steps to reproduce** | 1. Open [Main Page](https://jpetstore.mate.academy/actions/Catalog.action)<br>2. Add a product<br>3. Observe "In Stock" column |
|  | **Actual result** | Product not in stock yet added successfully |
|  | **Expected result** | Out-of-stock products should not be addable to Cart |
|  | **Attachments** | Screenshot: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-009.1.png), Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-009.2.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Major |

---

## 🐞 PS-010 - Added product not synced across sessions
| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-010 |
| **Summary** |  | [Logged-in user]: added product not displayed in all sessions |
| **Bug details** | **Preconditions** | Have account; two browsers/devices |
|  | **Steps to reproduce** | 1. Open [Login Page](https://jpetstore.mate.academy/actions/Account.action?signonForm=) on first browser<br>2. Make login with valid credentials<br>3. Click on Cart icon, make sure it is empty<br>4. Open [Login Page](https://jpetstore.mate.academy/actions/Account.action?signonForm=) on second browser<br>5. Make login with the same credentials used before<br>6. Click on Cart icon, make sure Cart is empty<br>7. Using the first browser, add a product to the Cart<br>8. Reload "Shopping Cart" page on second browser |
|  | **Actual result** | Cart not updated in second session |
|  | **Expected result** | Cart contents synced across all logged-in sessions |
|  | **Attachments** | Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-010.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Critical |

---

## 🐞 PS-011 - Logout resets Cart for logged-in user
| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-011 |
| **Summary** |  | Logging out with non-empty Cart clears it after login |
| **Bug details** | **Preconditions** | Have account, non-empty Cart |
|  | **Steps to reproduce** | 1. Open [Login Page](https://jpetstore.mate.academy/actions/Account.action?signonForm=)<br>2. Click on Cart icon, make sure Cart is empty<br>3. Add a product to the Cart<br>4. Click on "Sign Out" link on header<br>5. Click on "Sign In" link on header<br>6. Login<br>7. Click on Cart icon |
|  | **Actual result** | Cart empty after re-login |
|  | **Expected result** | Cart should persist across logout/login |
|  | **Attachments** | Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-011.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Critical |

---

## 🐞 PS-012 - Product removed from Cart is not removed from all sessions

| **Category** | **Field** | **Value** |
|---------------|------------|------------|
| **ID** |  | PS-012 |
| **Summary** |  | Product removed from Cart is not removed from all sessions |
| **Bug details** | **Preconditions** | Have an account, non-empty cart, two different browsers (Chrome, Firefox, Opera, etc.) or devices (desktop, mobile) |
|  | **Steps to reproduce** | 1. Open "Shopping Cart" page in first browser<br>2. Open "Shopping Cart" page in second browser<br>3. Click "Remove" in first browser<br>4. Reload "Shopping Cart" page in second browser |
|  | **Actual result** | Product is removed in first browser but still visible in the second one |
|  | **Expected result** | Removing a product from Cart should remove it from all active sessions |
|  | **Attachments** | Video: [link](https://github.com/Roksolana-K/manual-qa-portfolio/blob/main/jpetstore-cart-testing/attachments/PS-012.mp4) |
| **Environment** | **Operating system** | Windows 11 |
|  | **App version** | Demo |
|  | **Browser** | Chrome (latest) |
| **Severity** |  | Critical |

---
