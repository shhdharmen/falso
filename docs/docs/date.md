# Date

### `randMonth`

Generate a random month.

```ts
import { randMonth } from '@ngneat/falso';

month();
month({ length: 10 });
```

### `randBetweenDate`

Generate a random date between ranges.

```ts
import { randBetweenDate } from '@ngneat/falso';

randBetweenDate();
randBetweenDate({ from: Date, to: Date });
randBetweenDate({ length: 10 });
```

### `randFutureDate`

Generate a random future.

```ts
import { randFutureDate } from '@ngneat/falso';

randFutureDate();
randFutureDate({ length: 10 });
randFutureDate({ years: 10 });
```

### `randPastDate`

Generate a random past date.

```ts
import { randPastDate } from '@ngneat/falso';

randPastDate();
randPastDate({ years: 2 });
randPastDate({ length: 10 });
```

### `randRecentDate`

Generate a random recent date.

```ts
import { randRecentDate } from '@ngneat/falso';

randRecentDate();
randRecentDate({ days: 10 });
randRecentDate({ length: 10 });
```

### `randSoonDate`

Generate a random soon.

```ts
import { randSoonDate } from '@ngneat/falso';

randSoonDate();
randSoonDate({ days: 5 });
randSoonDate({ length: 10 });
```

### `randWeekday`

Generate a random weekday.

```ts
import { randWeekday } from '@ngneat/falso';

randWeekday();
randWeekday({ length: 10 });
```
