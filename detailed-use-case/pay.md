### Use Case Name
Pay

### Trigger
The order was created successfully.

### Pre-condition
The customer has decided to pay for the existing order.

### Basic Flow

1. The customer clicks on the `Pay` button.
2. The system provides some ways of purchasing such as Paypal.
3. The customer selects one way to pay.
4. The system redirects to the paying website.
5. The customer fills out the information required to pay.
6. The paying website notifies the system that the paying process is complete.
7. The order management systems marks the order as paid.
8. The system notifies the customer that paying is finished.

### Post-condition
The order gets paid for.

### Exception Flow
The customer may change his/her mind and want to cancel the order.