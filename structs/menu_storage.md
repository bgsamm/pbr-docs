# struct MENU_STORAGE

Size: ``

| Offset   | Name            | Type  | Notes |
| -------- | --------------- | ----- | ----- |
| `0x88`   | ???             | int   | some sort of index |
| `0xce`   | stateBitfield   | short | |
| `0xd0`   | filtersBitfield | short | |
| `0x27a8` | ???             | ???   | size=0x44 |

stateBitfield

| Label       | Bits | Values |
| ----------- | ---- | ------ |
| currentBox  | 0:5  | |
| currentCell | 6:10 | |
| moveDir     | 11:12 | 1 - up/left; 2 - down/right |
|  | 13:14 | |
| ??? | 15 | |

filtersBitfield

| Label       | Bits | Values |
| ----------- | ---- | ------ |
| | 9:14 | |