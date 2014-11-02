### Use Case Name
Paying

### Trigger
The order was created with default status `awaiting payment`.

### Pre-condition
The customer signs in the Midway system (via SPL in taobao.com), then heads over to `My Orders`.

### Basic Flow
 
1. The customer clicks on the `Pay` button on one of the unpaid order.
2. The system lists all supported payment gateway, such as via Paypal or Alipay.
3. The customer selects one payment gateway and click `Pay Now`.
4. The system redirects to the payment gateway.
5. The customer follows process provided in the payment gateway, and got redirected to the 6. Midway system again.
7. The system redirects the customer to choose delivery destination.

### Post-condition
The order gets paid for.

### Alternative Flow
1. The customer chooses to purchase offline in step 2.
2. The system redirects the customer to choose delivery destination.

### Exception Flow
The customer may change his/her mind and want to cancel the order.