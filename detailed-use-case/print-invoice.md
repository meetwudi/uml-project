### Use Case Name
Print invoice

### Trigger
The order has been paid for.

### Pre-condition
The customer asks for invoices of this paid order.

### Basic Flow
1. The customer clicks on `Print invoice` button after paying.
2. The system displays the form of invoice information.
3. The customer fills out the form.
4. The system generates invoice in the pdf filetype.
5. The customer clicks the `My Orders` button.
6. The system display the customer's orders list.
7. The customer clicks the `Download Invoice` button to download the invoice and gets it printed.

### Post-condition
The invoice gets printed by customer.

### Exception Flow
The customer doesn't provide the required information about the invoice, so the system will ask the customer to fill in again.