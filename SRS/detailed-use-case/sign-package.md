### Use Case Name
Sign package

### Trigger
The customer meets the delivery person at home.

### Pre-condition
1. Before this use case can be initialized, the customer should sign in the Midway system (via SSO in taobao.com).
2. The package should be delivered to the customer.

### Basic Flow
1. The customer signs on the pad to leave a signature or a fingerprint.
2. The logistics company's employee transfers the signature data to the server.
3. The order management subsystem records the signature data and change the status of the order to `Confirmed`.

### Post-condition
The order is marked complete.

### Exception Flow
The customer may find the package broken or damaged and want to return the package.