```c
int HEAP::ALLOC(int size, int alignment=0x20)
```

#### Description

Allocates a block of memory on the heap with a specified memory alignment.

#### Parameters
  - `size` - description
  - `alignment` - a factor the memory's address should be a multiple of; should be a power of 2

#### Returns

The address of the allocated memory

#### Location

| Region      | Address      | w/ default |
| ----------- | ------------ | ---------- |
| NTSC-J      | `???`        | `???`      |
| NTSC-U      | `8029b90c`   | `801df8d4` |
| PAL         | `???`        | `???`      |