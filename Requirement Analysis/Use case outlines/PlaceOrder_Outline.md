Basic flow:
1. Customer reviews the cart and select the products they want to purchase
2. Customer requests to place order
3. Software checks availibility of the products
4. Software asks the customer to setup delivery information
5. Customer provides delivery information
6. Software calculates order cost and the delivery fee
7. Customer selects payment method and provide payment information
8. Software displays and sends order and transaction information to customer's email

Alternative flow:
- Exception:
+ At step 3: Software asks customer to update the cart if any product is unavailable
+ At step 5: Invalid delivery information
+ At step 7: Invalid payment information
+ At step 8: Not enough balance

Option case: Customer places rush order