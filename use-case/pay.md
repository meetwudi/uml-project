# Use Case: Paying

### Diagram


### Brief Introduction
The customer pays the bill.


### Initial Step-by-Step  
Before this use case can be initialized, the customer signs in the Midway system (or via SPL in taobao.com), then heads over to `My Orders`.

 
1. The customer clicks on the `Pay` button.
2. The system provides various means of purchasing, such as via Paypal or Alipay.
3. The customer selects one way to pay.
4. The system redirects to the payment gateway.
5. The customer follows process provided in the payment gateway, and got redirected to the Midway system again.
6. The system displays the orders list with the payed items marked `paid, awaiting for delivery`.