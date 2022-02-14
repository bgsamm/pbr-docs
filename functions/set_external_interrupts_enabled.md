```c
bool SET_EXTERNAL_INTERRUPTS_ENABLED(bool enable)
```

#### Description

Sets the EE (external interrupt enable) bit of the MSR

#### Parameters
  - `enable` - the value to set the MSR[EE] bit to

#### Returns

The old value of the MSR[EE] bit

#### Location

| Region      | Address      |
| ----------- | ------------ |
| NTSC-J      | `???`        |
| NTSC-U      | `8027312c`   |
| PAL         | `???`        |