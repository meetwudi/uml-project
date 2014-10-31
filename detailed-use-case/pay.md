### Use Case Name
Paying

### Trigger
The order was created with default status `awaiting payment`.

### Pre-condition
The customer signs in the Midway system (via SPL in taobao.com), then heads over to `My Orders`.

### Basic Flow
 
1. The customer clicks on the `Pay` button.
2. The system provides various means of purchasing, such as via Paypal or Alipay.
3. The customer selects one way to pay.
4. The system redirects to the payment gateway.
5. The customer follows process provided in the payment gateway, and got redirected to the Midway system again.
6. The system displays the orders list with the payed items marked `paid, awaiting for delivery`.

### Post-condition
The order gets paid for.

### Alternative Flow
1. The customer may want to purchase offline.
He/She should pay for the order when he/she receives the package.
2. The customer doesn't have enough money.
He/She can pay later.

### Exception Flow
The customer may change his/her mind and want to cancel the order.