### Use Case Name

Get Damage Information



### Trigger

The information about the damaged or lost package is sent to the customer by text message.



### Pre-condition

Before this use case can be initialized, the system has sent the information about the damage or lost of the package to the customer and the logistics company.



### Basic Flow




1. The customer gets the information of the damage or lost of the package by text message.
2. The customer selects the seller to deliver the package again or cancel the order. 
3. The customer replys the message sent by the text messaging system to tell the system his/her decision.


### Post-condition

The order management system gets the customer's decision to the package.



### Exception Flow

In step 1 if the customer input the wrong phone number, the order tracking system will highlight the damaged or lost package iterm in the customer's account so that the customer will see it when the customer logs in next time.

In step 3 if the customer reply a message in wrong format, the text messaging system will sent the customer a warnning message and the customer can deal with the information on website again.


### Alternative Flow

In step 3, the customer can also log in his/her account on website to deal with the information, in use case cancel order and request redelivery. 