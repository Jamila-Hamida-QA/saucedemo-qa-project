Test Cases - SauceDemo

## Type: Manual Testing (Functional + UI + Edge Cases)


# 🔐 LOGIN MODULE

### TC_LOGIN_01 - Valid Login
**Precondition:** User is on login page  
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter username: standard_user
3. Enter password: secret_sauce
4. Click Login  

**Expected Result:** User redirected to Products page. 
**Priority:** High  


### TC_LOGIN_02 - Invalid Password
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter valid username
3. Enter wrong password
4. Click Login
   
**Expected Result:** Error message displayed : "Epic sadface: Username and password do not match any user in this service"  
**Priority:** High  



### TC_LOGIN_03 - Invalid Username
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter an invalid username (e.g = test)
3. Enter wrong password 
4. Click Login 

**Expected Result:** Login fails with error : "Epic sadface: Username and password do not match any user in this service"
**Priority:** High  



### TC_LOGIN_04 - Locked User Login
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter a locked username: "locked_out_user"
3. Enter wrong password
4. Click Login 
**Expected Result:** User locked error displayed: "Epic sadface: Sorry, this user has been locked out."  
**Priority:** High  



### TC_LOGIN_05 - Empty Fields
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Click Login (Without filling Username and Password fields)
**Expected Result:** Error message displayed : "Username and Password are required"
**Priority:** High  



### TC_LOGIN_06 - Empty Username
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Keep the Username field empty. 
3. Enter a valid password
4. Click Login 
**Expected Result:** Error displayed : "Epic sadface: Username is required"
**Priority:** High  



### TC_LOGIN_07 - Empty Password
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter a valid username
3. Keep the password field empty
4. Click Login 
**Expected Result:** Error displayed : "Epic sadface: Password is required" 
**Priority:** High  



### TC_LOGIN_08 - Case Sensitivity Check
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter valid username in upper case.
3. Enter valid password in upper case.
4. Click Login 
**Expected Result:** Login fails and an Error displayed : "Epic sadface: Username and password do not match any user in this service".
**Priority:** Medium  

 

### TC_LOGIN_10 - Refresh Login Page
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter valid username.
3. Enter valid password.
4. Refresh Login page. 
**Expected Result:** Page resets correctly.  
**Priority:** Low  

---

# 🛍️ PRODUCTS MODULE

### TC_PROD_11 - Product List Display
**Steps:**
1. Open SauceDemo : https://www.saucedemo.com/
2. Enter valid username.
3. Enter valid password.
4. Click Login. 
**Expected Result:** All products visible  
**Priority:** High  

----------------------------------------------------------------

### TC_PROD_12 - Product Images Load
**Expected Result:** Images displayed correctly  
**Priority:** Medium  

---

### TC_PROD_13 - Add Product to Cart
**Expected Result:** Cart badge updates  
**Priority:** High  

---

### TC_PROD_14 - Remove Product from Cart
**Expected Result:** Cart updates correctly  
**Priority:** High  

---

### TC_PROD_15 - Sort A to Z
**Expected Result:** Products sorted alphabetically  
**Priority:** Medium  

---

### TC_PROD_16 - Sort Price Low to High
**Expected Result:** Correct order  
**Priority:** Medium  

---

### TC_PROD_17 - Sort Price High to Low
**Expected Result:** Correct order  
**Priority:** Medium  

---

### TC_PROD_18 - Add Multiple Items
**Expected Result:** Multiple items added correctly  
**Priority:** High  

---

### TC_PROD_19 - Refresh Products Page
**Expected Result:** State maintained  
**Priority:** Low  

---

### TC_PROD_20 - UI Layout Check
**Expected Result:** No UI issues  
**Priority:** Low  

---

# 🛒 CART MODULE

### TC_CART_21 - View Cart Items
**Expected Result:** Items displayed  
**Priority:** High  

---

### TC_CART_22 - Remove Item from Cart
**Expected Result:** Item removed successfully  
**Priority:** High  

---

### TC_CART_23 - Continue Shopping
**Expected Result:** Redirects to products page  
**Priority:** Medium  

---

### TC_CART_24 - Checkout Button Enabled
**Expected Result:** Enabled when items exist  
**Priority:** High  

---

### TC_CART_25 - Empty Cart Checkout Disabled
**Expected Result:** Checkout blocked  
**Priority:** High  

---

### TC_CART_26 - Cart Badge Accuracy
**Expected Result:** Correct count displayed  
**Priority:** High  

---

### TC_CART_27 - Cart Persistence After Refresh
**Expected Result:** Items remain  
**Priority:** Medium  

---

### TC_CART_28 - Remove All Items
**Expected Result:** Cart becomes empty  
**Priority:** High  

---

# 💳 CHECKOUT MODULE

### TC_CHECKOUT_29 - Valid Checkout Flow
**Expected Result:** Order completed successfully  
**Priority:** High  

---

### TC_CHECKOUT_30 - Empty First Name
**Expected Result:** Validation error  
**Priority:** High  

---

### TC_CHECKOUT_31 - Empty Last Name
**Expected Result:** Validation error  
**Priority:** High  

---

### TC_CHECKOUT_32 - Empty Postal Code
**Expected Result:** Validation error  
**Priority:** High  

---

### TC_CHECKOUT_33 - Order Summary Verification
**Expected Result:** Correct total displayed  
**Priority:** High  

---

### TC_CHECKOUT_34 - Cancel Checkout
**Expected Result:** Returns to cart  
**Priority:** Medium  

---

### TC_CHECKOUT_35 - Finish Order
**Expected Result:** Success message shown  
**Priority:** High  

---

### TC_CHECKOUT_36 - Refresh Checkout Page
**Expected Result:** No data loss  
**Priority:** Low  

---

# 🔁 EDGE CASES

### TC_EDGE_37 - Multiple Login Clicks
**Expected Result:** No duplicate sessions  
**Priority:** Medium  

---

### TC_EDGE_38 - Session Timeout During Checkout
**Expected Result:** Redirect to login  
**Priority:** High  

---

### TC_EDGE_39 - Multiple Tabs Open
**Expected Result:** Session handled correctly  
**Priority:** Medium  

---

### TC_EDGE_40 - Rapid Add/Remove Cart Actions
**Expected Result:** Cart remains consistent  
**Priority:** High  

---
