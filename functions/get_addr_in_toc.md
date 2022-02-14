```c
int GET_ADDR_IN_TOC(int fsysID)
```

#### Description

Finds the entry associated with a given fsys ID in GSfsys.toc.

#### Parameters
  - `fsysID` - the ID of the fsys file to search for

#### Returns

The memory address of the found entry. Returns 0 if not found.

#### Location

| Region      | Address      |
| ----------- | ------------ |
| NTSC-J      | `???`        |
| NTSC-U      | `8024c32c`   |
| PAL         | `???`        |