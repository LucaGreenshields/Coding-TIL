# Dispatch tables

what they are:
 dispatch table in Python is basically a dictionary of functions.

when you would use them:
You would use them instead of an if-elif statments

* efficient
* robust

how to code them

```python

import datetime

dispatch = {
  0: do_monday,
  1: do_tuesday,
  2: do_wednesday,
  3: do_thursday,
  4: do_friday,
  5: do_saturday,
  6: do_sunday
}
my_special_day = datetime.date(2019, 5, 25)

dispatch[my_special_day.weekday()]()
```
