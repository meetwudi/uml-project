### Use Case Name
Cancel order

### Trigger
1. The package was damaged or lost.
2. The customer ordered the wrong product.

### Pre-condition
Before this use case can be initialized, the customer should signs in the Midway system (via SSO in taobao.com), then heads over to “My Orders”.

### Basic Flow

1. The customer clicks the “Cancel order” button on the order he/she wants to cancel.
2. The system prompts if customer decided to cancel the order.
3. The customer chooses “yes”.
4. The order management system sends the customer's decision to the seller.
5. The seller confirms the cancellation.
6. The system notifies Taobao.com.


### Post-condition
The order gets canceled.

### Exception Flow
The customer may change his/her mind and want to change a new product instead.

### Alternative Flow
1. Before step 1, the system will send text message to inform user the process of cancelling order by text messaging.
2. The customer can cancel order by replying the system's text message.