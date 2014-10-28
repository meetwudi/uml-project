### Use Case Name
Request Redelivery

### Trigger
The package was damaged or lost and the customer decided to request redelivery.

### Pre-condition
The customer has decided to request redelivery of the product after he/she get the information.

### Basic Flow

1. The customer access the system and login with the account.
2. The order tracking system display the User Center to the customer.
3. The customer clicks the `My Orders` button.
4. The order tracking system display the customer's orders list and highlight the package that has been damaged or lost.
5. The customer clicks the `Redelivery` button.
6. The order tracking system prompt to ask if customer decided to let the package be delivered again.
7. The customer chooses `yes`.
8. The order management system sends the customer's decision to the logistic company and the seller.
9. The logistic company and the seller start the redelivery.

### Post-codition
A new product get send to the customer.

### Exception Flow
The customer may change his/her mind and want to cancle the order instead.


### Alternative Flow
The customer can finish these steps by replying the system's text message.