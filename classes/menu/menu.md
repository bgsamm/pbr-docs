# class MENU

[Fields](#fields) [Methods](#methods)

Size: `0x158`

#### Fields

| Offset  | Name          | Type              | Notes |
| ------- | ------------- | ----------------- | ----- |
| `0x0`   | count         | short             | |
| `0x2`   | nextIndex     | short             | |
| `0x4`   | headers       | MNR[]             | size = count |
| `0x8`   | groups        | COMPONENT_GROUP[] | size = count |
| `0xc`   | funcPtrs      | int[][3]          | size = count |
| `0x10`  | ???           | short[]           | size = count |
| `0x14`  | ???           | ???               | mem. size = 0x3d4 |
| `0x18`  | components    | COMPONENT[]       | size = count * 64 |
| `0x1c`  | ???           | int               | |
| `0x20`  | maxComponents | int               | count * 64 |
| `0x24`  | ???           | int               | |
| `0x28`  | ???           | int               | |
| `0x2c`  | ???           | int[32]           | list of function ptrs |
| `0xac`  | ???           | int[32]           | list of function ptrs |
| `0x12c` | ???           | bool[32]          | |
| `0x14c` | ???           | int               | |
| `0x150` | ???           | int               | |
| `0x154` | ???           | int               | |

#### Methods

| Name | NTSC-J     | NTSC-U     | PAL        |
| ---- | ---------- | ---------- | ---------- |
| [MENU::MENU](classes/menu/menu_menu.md) | `???`      | `80255b30` | `???`      |
| [MENU::INIT_MNR_SECTION_1](classes/menu/menu_init_mnr_section_1.md) | `???`      | `8025652c` | `???`      |
| [MENU::PLAY_ANIM](classes/menu/menu_play_anim.md) | `???`      | `802585ac` | `???`      |

[Back to top](#class-menu)
