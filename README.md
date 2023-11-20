### Multiplication Function
<hr>
Expectations
- The function to receive two integer numbers as arguments
- The function to multiply the two interger or float numbers
- The function should return the result of the multiplaication
- The function should not receieve empty, undefined, or null arguments
<hr>

### Unit Tests
Expect multiplication to be correct
- Expect 'multiplaication (4, 6)' to be interger or float numbers
- Expect 'multiplaication (4, 6)' to be 24
- Expect 'multiplaication (4, -2)' to be -8
- Expect 'multiplaication (0, 5)' to be 0

Expect multiplication to be an error
- Expect 'multiplaication (a, 5)' to be an error
- Expect 'multiplaication ({ }, 2)' to be an error
<hr> 

### Functional Tests
- Given: I am a user with guest account or registered account in the site.
- When: I click on the checkout button, if I am logged in it will bring me to the checkout page
- When I click on the checkout button, if i dont have an account it will ask if i want to continue as guest or create an account

<hr>

### Shopping Cart

#### Expectations:
- Users should be able to add items to their shopping cart.
- Users should view the items in their cart.
- Users should be able to remove items from their cart.
- The cart should display the total price of all items.

#### Functional Tests:
 Expect items to be added to the cart:**
   - Given a user adds an item to the cart, verify the item appears in the cart.

 Expect items to be visible in the cart:**
  - Given a user has added items to the cart, verify the cart displays these items.

 Expect items to be removed from the cart:**
   - Given a user removes an item from the cart, verify the item is no longer present in the cart.
