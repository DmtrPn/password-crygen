# password-crypto


#### Install

`yarn add password-crygen`

#### Generate password hash

```typescript
import { generatePasswordHash } from 'password-crypto';

const password = '123qwe';
const passwordHash = generatePasswordHash(password);
```

#### Check password

```typescript
import { checkPassword } from 'password-crypto';

const passwordToChech = '123qwe';
const passwordHash = 'hex...';
const isSame = checkPassword(passwordToChech, passwordHash);
```


