### Use Case Name
Reschedule Delivery

### Trigger
The customer is not at home and no agent for him/her and the delivery need to be rescheduled.

### Pre-condition
1. The customer should sign in the Midway system(via SSO in taobao.com).
2. The customer has already ordered a product and the customer is not at home and no agent for him/her.

### Basic Flow

1. The customer chooses to reschedule the delivery.
2. The order management sub-system displays the form of rescheduling.
3. The customer fills out the information required and submit it.
4. The order management sub-system receives the request, confirms it and sends the information of rescheduling to the logistics company.
5. The logisics company's employee takes the package to the customer on reschedular day.

### Post-condition
The delivery is rescheduled.

### Exception Flow
The customer may have time to receive the product suddenly and the delivery isn't rescheduled.
