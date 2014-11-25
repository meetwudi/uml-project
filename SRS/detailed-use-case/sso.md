# Use Case Name
Single Sign On

### Trigger
The user wants to sign in Midway system with his/her own Taobao account.

### Pre-condition
1. The user has a valid Taobao account.
2. The user is not signed in.

### Basic Flow
1. The user access the Midway system.
2. The system redirect the user to `member1.taobao.com`.
3. The user fill out the informations required.
4. The system validate the informations and redirect the user back to the Midway system.

### Post-condition
The user is successfully signed on.

### Exception Flow
In Step 4, the system may find the informations invalid. In that case, the user will be required to repeat step 3 again until his/her information is valid.