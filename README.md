# yyyymmdd-types

You can use type YYYYMMDD strictly.

```ts
import { YYYYMMDDDate } from './yyyymmdddate';

// eslint-disable-next-line @typescript-eslint/no-unused-vars
const d: YYYYMMDDDate = { year: 2021, month: 10, day: 31 };
```

```ts
import { YYYYMMDDDate } from './yyyymmdddate';

// eslint-disable-next-line @typescript-eslint/no-unused-vars
const d: YYYYMMDDDate = { year: 2021, month: 2, day: 31 };
//                                        Error ^^^^^^^
//                                                 |
//               Types of property 'day' are incompatible.
//         Type '31' is not assignable to type 'Day1To28'.
```
