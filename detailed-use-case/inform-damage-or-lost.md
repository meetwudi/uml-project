### Use Case Name

Inform Damaged Or Lost



### Trigger

The package is damaged or missing.



### Pre-condition

The customer has ordered a package and the package is on the way.



### Basic Flow



1. The logistics company employee records the damage or lost and inputs the information to the order tracking system.
2. The order management system sends the information to the seller.
3. The text messaging system sends the information and an apology to the customer by text message.
4. The customer gets the information of the damage or lost of the package by text message.
5. The customer selects the seller to deliver the package again or cancel the order. 
6. The customer replys the message sent by the text messaging system to tell the system his/her decision.


### Post-condition

The customer and the seller get informed.



### Exception Flow

In step 3 if the customer input the wrong phone number, the order tracking system will highlight the damaged or lost package iterm in the customer's account so that the customer will see it when the customer logs in next time.

In step 6 if the customer reply a message in wrong format, the text messaging system will sent the customer a warnning message and the customer can deal with the information on website again.


### Alternative Flow

In step 6, the customer can also log in his/her account on website to deal with the information, in use case cancel order and request redelivery. 