# 📝 Requirements: PetStore Cart Feature

## 1. General requirements
- Users should be able to access the Cart from any page in the app.
- The Cart icon should have a tooltip ‘Cart’. 
- In the cart, there should be info about added products. All info about added products should be in the table with columns: 
  - Item ID
  - Product ID
  - Name
  - Description
  - In Stock?
  - Quantity
  - List Price
  - Total Cost.
- The last row in the product table should contain info about the total price, named “Sub Total”, and a button to update all products in the cart, named “Update Cart ”.
- The Cart by default should not contain products. Empty Cart should contain “Your cart is empty.” text.
- The button “Proceed to Checkout” should be present under the table if at least one product was added to the Cart.
- The “Proceed to Checkout” button should redirect logged-in users to the Checkout page. Not logged-in users should be redirected to the Login page.
- Users should be able to leave the Cart page by clicking on the “Return to Main Menu” link.


## 2. Adding and removing products
- To add products to the cart, users have to click on the “Add to Cart” button:
  - from the Product Details Page (PDP);
  - from the list of products.
- When a user adds a new product to a Cart, it should be displayed as a badge with a quantity of added to the Cart products on the Cart’s icon. [Example](https://prnt.sc/xHvxLUp9zCGq)
- The product in the cart should contain clickable links for the product “Item ID” and “Name”.
- The “Quantity” field in the Cart should accept only numbers.
- Users shouldn’t be able to add more than 5 items of the same products per order. 
- Validation of the quantity should happen immediately after a user enters a new quantity and presses Enter or clicks on the “Update Cart” button. 
- The validation message should be shown under the table in case of the appropriate situation:
  - “We are sorry, but you can’t buy more than 5 items of the product.”
  - “We are sorry, but we have only N items of this product for now. Would you like to subscribe to notifications when this product will be available?“
- Users should be able to remove products from the Cart by clicking on the “Remove” button near the product price. 
- If user enters the quantity of the product as 0 (zero) and updates the cart by the “Update Cart” button, it also should be removed from the Cart.
- The user should not be able to add the product to the Cart if it is not in stock.


## 3. Cross-session Cart
- If a logged-in user adds a product to the Cart, it should be displayed on all other sessions. 
- When logged-in users add an item to the Cart and log out, the Cart should become empty for this session.
- When users remove a product from the Cart, it should be removed from all other sessions.
