# Cart Test Cases – SauceDemo

## TC-CART-01 – Add product to cart

**Preconditions:**
- User is logged in
- User is on inventory page

**Steps:**
1. Click "Add to cart" button for Sauce Labs Backpack
2. Observe the cart icon
3. Click the cart icon

**Expected Result:**
- Product is added to cart
- Cart badge shows "1"
- Sauce Labs Backpack is displayed in the cart

**Status:** PASS

**Notes:** all UI elements and data are correctly displayed

---

## TC-CART-02 – Remove product from cart

**Preconditions:**
- User is logged in
- Product is already added to cart

**Steps:**
1. Open the cart page
2. Click "Remove" button for the product

**Expected Result:**
- Product is removed from cart
- Cart badge is no longer displayed
- Cart page no longer shows the removed product

**Status:** Not executed

---

## TC-CART-03 – Cart badge updates correctly

**Preconditions:**
- User is logged in
- User is on inventory page

**Steps:**
1. Add one product to cart
2. Add a second product to cart
3. Remove one product

**Expected Result:**
- Cart badge shows "1" after first product
- Cart badge shows "2" after second product
- Cart badge returns to "1" after removing one product

**Status:** PASS

**Notes:** Badge correctly reflects number of items in cart in all scenarios.

---

## TC-CART-04 – Cart retains selected items after navigation

**Preconditions:**
- User is logged in
- Product is added to cart

**Steps:**
1. Add Sauce Labs Backpack to cart
2. Navigate to cart page
3. Return to inventory page
4. Open cart page again

**Expected Result:**
- Selected product remains in the cart
- Cart badge remains consistent

**Status:** Not executed
