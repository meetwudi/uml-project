### Use Case Name
Sign the Package by Agent

### Trigger
The customer is not convenient to sign the package.

### Pre-condition
The customer has ask a agent to receive for him/her.

### Basic Flow

1. The customer asks agent to receive the package for him/her and register the checking information of the agent digitally.
2. The logistic company's employee gets the package, checks the delivery information and get confirmation from the agent by text messaging sub-system.
3. The agent sends confirmation to the logistic company's employee through messaging sub-system.
4. The logistic company's employee delivers the package to the appointed place on schedule.
5. The agent fills out the checking information digitally.
6. The logistic company's confirms the agent is the right person.
7. The agent signs the package digitally.
8. The logistics company's employee transfers the signature data to the server.
9. The order management subsystem records the signature data and change the status of the order to `Confirmed`.

### Post-condition
The agent signs the package for the customer.

### Exception Flow
The agent who is asked to receive the package for customer suddently becomesbusy and inconvenient to sign the package.
