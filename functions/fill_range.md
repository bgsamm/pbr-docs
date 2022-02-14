```c
int FILL_RANGE(int address, char value, int size)
```

#### Description

Fills a range in memory with a single value (wraps [DO_FILL_RANGE](functions/do_fill_range.md)).

#### Parameters
  - `address` - the address to start filling from
  - `value` - the value to fill with
  - `size` - the size of the range to fill

#### Returns

The start address of the range

#### Location

| Region      | Address      |
| ----------- | ------------ |
| NTSC-J      | `80004104`   |
| NTSC-U      | `80004104`   |
| PAL         | `80004104`   |