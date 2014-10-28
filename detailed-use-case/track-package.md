### Use Case Name
Track package

### Trigger
The package is being delivered to the customer.

### Pre-condition
The customer should receive a tracking number for his/her package.

### Basic Flow
1. The customer access the system and login with the account.
2. The system display the User Center to the customer.
3. The customer clicks the `My Orders` button.
4. The system display the customer's orders list and highlight the package that is being delivered.
5. The customer clicks on `Track` button.
6. The system asks for a tracking number.
7. The customer enters the tacking number of the package he or she wants to track.
8. The system sends a tracking request to order tracking system.
9. The order tracking system returns the tracking information. 
10. The system displays the current location and transport information of the package.

### Post-condition
The customer gets the tracking information.

### Exception Flow
The customer may enter an invalid tracking number so that the operation is aborted.