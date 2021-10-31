# yyyymmdd-types

You can use date type strictly.

```ts
import { YYYYMMDDDate } from './yyyymmdddate';

const good: YYYYMMDDDate = { year: 2021, month: 10, day: 31 };

const bad: YYYYMMDDDate = { year: 2021, month: 2, day: 31 };
//                                          Error ^^^^^^^
//                                                   |
//                 Types of property 'day' are incompatible.
//           Type '31' is not assignable to type 'Day1To28'.
```
