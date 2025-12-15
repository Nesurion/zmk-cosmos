# Cosmos Keyboard - Key Position Map

This document shows the key position numbers for your 36-key split keyboard.
Key positions are used in combos, hold-tap behaviors, and other ZMK features.

## Visual Layout

```
╭─────────────────────────────────────╮ ╭─────────────────────────────────────╮
│  0   1   2   3   4                  │ │                   5   6   7   8   9 │
│  Q   W   E   R   T                  │ │                   Y   U   I   O   P │
│                                     │ │                                     │
│ 10  11  12  13  14                  │ │                  15  16  17  18  19 │
│  A   S   D   F   G                  │ │                   H   J   K   L   ; │
│                                     │ │                                     │
│ 20  21  22  23  24                  │ │                  25  26  27  28  29 │
│  Z   X   C   V   B                  │ │                   N   M   ,   .   / │
╰────────╮ 30  31  32                 │ │                  33  34  35 ╭───────╯
         │      TAB SPC                │ │                 ENT BSPC    │
         ╰────────────────────────────╯ ╰─────────────────────────────╯
            SHFT                                                 SHFT
```

## Position Reference

### Left Half (Central)
- **Top Row (0-4):**    Q W E R T
- **Home Row (10-14):** A S D F G
- **Bottom Row (20-24):** Z X C V B
- **Thumb Keys (30-32):** Left Shift, Tab, Space

### Right Half (Peripheral)
- **Top Row (5-9):**    Y U I O P
- **Home Row (15-19):** H J K L ;
- **Bottom Row (25-29):** N M , . /
- **Thumb Keys (33-35):** Enter, Backspace, Right Shift

## Total Keys: 36 (positions 0-35)

## Current Combos

Based on your keymap configuration:

- **ESC:** Positions 30 + 31 (Left Shift + Tab)
- **DELETE:** Positions 34 + 35 (Backspace + Right Shift)
- **CAPS_WORD:** Positions 30 + 35 (Left Shift + Right Shift)

## Homerow Mods

### Left Hand Mods (hml)
Applied to positions: 11 (S), 12 (D), 13 (F)
- Trigger on opposite hand keys: 5-9, 15-19, 25-35

### Right Hand Mods (hmr)
Applied to positions: 16 (J), 17 (K), 18 (L)
- Trigger on opposite hand keys: 0-4, 10-14, 20-24, 30-35

## Notes

- Valid key positions: **0-35** only
- Positions 36+ do not exist and will cause behaviors to be ignored
- This layout matches the matrix transform defined in `cosmos.dtsi`
