| Name            | Type    | NTSC-J     | NTSC-U     | PAL        | Description |
| --------------- | ------- | ---------- | ---------- | ---------- | ----------- |
| MEM2_START      | int     | `???`      | `80003124` | `???`      | Start of the usable memory in MEM2 |
| MEM2_END        | int     | `???`      | `80003128` | `???`      | End of the usable memory in MEM2 |
| SAVE_ADDR       | int     | `???`      | `8045de80` | `???`      | Address of the game's save data in memory |
| MEM2_FREE_START | int     | `???`      | `80625d94` | `???`      | Start of the free memory in MEM2 |
| MEM1_HEAP_1     | &HEAP   | `???`      | `80626c08` | `???`      | Pointer to the first heap in MEM1 (size 0x10b8f00) |
| MEM2_HEAP_5     | &HEAP   | `???`      | `80626c0c` | `???`      | Pointer to the fifth heap in MEM2 (size 0x1e8f800) |
| MEM2_HEAP_3     | &HEAP   | `???`      | `80626c10` | `???`      | Pointer to the third heap in MEM2 (size 0xc00000) |
| MEM2_HEAP_4     | &HEAP   | `???`      | `80626c14` | `???`      | Pointer to the fourth heap in MEM2 (size 0x100000) |
| MEM1_HEAP_2     | &HEAP   | `???`      | `80626c18` | `???`      | Pointer to the second heap in MEM1 (size 0x100000) |
| MEM1_FREE_END   | int     | `???`      | `80627d70` | `???`      | End of the free memory in MEM1 |
| MEM2_FREE_END   | int     | `???`      | `80627d74` | `???`      | End of the free memory in MEM2 |
| GTX_LOADERS     | GTX_LOADER[0x80] | `???`      | `80627a58` | `???`      | 126 instances of GTX_LOADER that get reused as needed |
| MEM2_HEAP_1     | &HEAP   | `???`      | `80627ab8` | `???`      | Pointer to the first heap in MEM2 (size 0x50000) |
| MEM2_HEAP_2     | &HEAP   | `???`      | `80627b18` | `???`      | Pointer to the second heap in MEM2 (size 0x800000) |
| IS_TOC_LOADED   | bool    | `???`      | `80627b46` | `???`      | Flags whether GSfsys.toc has been loaded |
| TOC_ADDR        | int     | `???`      | `80627b5c` | `???`      | Address of GSfsys.toc in memory |
| FSYS_LOADERS    | FSYS_LOADER[4] | `???`      | `80627b60` | `???`      | 4 instances of FSYS_LOADER that get reused as needed |
| FILENAME_LIST   | int     | `???`      | `80627fb4` | `???`      | Address of the game's list of filenames |
| FILE_TREE       | int     | `???`      | `80627fb8` | `???`      | Address of the game's file tree data |