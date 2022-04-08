# password-crypto


#### Install

`yarn add password-crygen`

#### Generate password hash

```typescript
import { generatePasswordHash } from 'password-crygen';

const password = '123qwe';
const passwordHash = generatePasswordHash(password);
```

#### Check password

```typescript
import { checkPassword } from 'password-crygen';

const passwordToChech = '123qwe';
const passwordHash = 'hex...';
const isSame = checkPassword(passwordToChech, passwordHash);
```


