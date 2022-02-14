# class FSYS_LOADER

[Fields](#fields) [Methods](#methods)

Size: `0x48`

#### Fields

| Offset | Name       | Type       | Notes |
| ------ | ---------- | ---------- | ----- |
| `0x0`  | FSYS_ID    | int        | |
| `0xc`  | INFO       | FILE_INFO  | |
| `0x10` | ???        | int        | |
| `0x14` | STATE      | STATE      | |
| `0x18` | NEXT_STATE | STATE      | |
| `0x1c` | TOC_ADDR   | int        | |
| `0x20` | ???        | int        | |
| `0x24` | ???        | int        | |
| `0x28` | ???        | int        | |
| `0x2c` | ???        | char       | |
| `0x2d` | ???        | char       | |
| `0x2e` | ???        | char       | |
| `0x30` | ???        | int        | |
| `0x34` | ???        | int        | |
| `0x38` | ???        | int        | |
| `0x40` | ???        | int        | |
| `0x44` | ???        | int        | |

#### Methods

| Name | NTSC-J     | NTSC-U     | PAL        |
| ---- | ---------- | ---------- | ---------- |

#### enum STATE

| Value    | Name  | Notes |
| -------- | ----- | ----- |
| `0x0`    | EMPTY | |
| `0x1`    | ???   | |
| `0x2`    | ???   | |
| `0x3`    | ???   | |
| `0x4`    | ???   | |
| `0x5`    | ???   | |
| `0x6`    | ???   | |
| `0xa`    | ???   | |
| `0xb`    | ???   | |
| `0xc`    | ???   | |
| `0xffff` | NULL  | |

[Back to top](#class-name)