
# The Typing of the Dead (Dreamcast) – European Keyboard Compatibility Patches

## Overview
These patches improve compatibility with **UK** and **German** keyboard layouts when playing the **USA version (v1.004 GDI)** of *The Typing of the Dead* on the Sega Dreamcast.

## Background
*The Typing of the Dead* was officially released on Dreamcast in **Japan** and **North America**, but never in Europe. As a result, the game was only designed to work correctly with keyboard layouts for those regions.

When using a European keyboard, many keys may be mismapped or unresponsive—especially special characters and punctuation. This can make gameplay difficult or frustrating.

## What These Patches Do
These patches modify the game’s internal keyboard mapping tables to better match common European keyboard layouts, specifically:

- **UK (British)** layout  
- **German (QWERTZ)** layout

This allows for more accurate and familiar key input when using these keyboards, hopefully improving usability and accessibility.

## 🔧 Patch Details

### UK Layout Patch Notes
- Patch filename : `Typing of the Dead, The - UK Keyboard.dcp`
- The main game is mostly playable with a UK keyboard even without the patch, as there are relatively few layout differences. However, **some special characters in the Training games may be difficult to input** without it, making the patch especially helpful in those cases.
- The **UK `#` key** (located above the right Shift key and to the left of the Enter key) does **not exist on US keyboards**, and although it has been mapped in the patch, it remains **non-functional in-game**. As a workaround, the `#` symbol is also kept on **`Shift+3`**, and the **`£` symbol has been omitted**, as it is unlikely to be needed during gameplay.

### German Layout Patch Notes
- Patch filename : `Typing of the Dead, The - DE Keyboard.dcp`
- **German-specific characters such as Ä, Ö, Ü, and ß do not function in the game**, even when mapped. These have been substituted with their non-accented equivalents (A, O, U), and ß is omitted entirely.
- The `=` key does not function in its standard German position. This may be due to the game expecting it **not to be used with Shift**, but that is speculation and the exact reason is unknown.
- **All required keys for gameplay are patched**, with one exception: **the German `#`/`'` key (“Hash"/"Apostrophe”)** does **not exist on US keyboards**, and while the patch attempts to map those characters to it, the key remains **non-functional in-game**. As a workaround, `#` is kept on **`Shift+3`**, and the **apostrophe `'` is moved to the key left of Backspace**, which is known to work reliably, but may be unfamiliar to you.  On a recommendation I also mapped apostrophe `'` to `Shift+ä` (just one key to the left), as it is similar to the intended location and may be helpful for muscle-memory.

### French (AZERTY) Layout Patch Notes
- Patch filename : `Typing of the Dead, The - DE Keyboard.dcp`
- Very special thanks to [Hinoroni](https://github.com/Hinoroni) who has submitted an updated version of their AZERTY patch to be included in this repository.  Hino says:
- - _I reordered the layout to maximize the number of special characters. I replaced `é`, `è`, `ç`, and `à`, with their 3rd characters._
- - _I also moved:_
- - - _`.` to `§`_
- - - _`#` to `^`_
- - - _`%` to `¨`_
- - - _`%` and `.` sometimes come in arcade mode and `#` often comes in drill mode so they needed to be reassigned._
- _`[`, `]`, `{`, `}`, `+`, `=`, `<`, `>` and `\` are left unassigned but I don't think they are used outside of training mode._
- @Hinoroni's original `xdelta` patch for AZERTY keyboard layouts is also available from the [Dreamcast-Talk Forum](https://www.dreamcast-talk.com/forum/viewtopic.php?p=190356) if you prefer to use it.


## 📎 Patch Information
- **Patch format**: `.dcp` (Dreamcast Patch File)
- **Base version required**: **USA v1.004 GDI**
- **Patching tool**: [Universal Dreamcast Patcher](https://github.com/DerekPascarella/UniversalDreamcastPatcher)

### Installation Instructions
1. Obtain a clean **GDI dump of the USA v1.004 version** of *The Typing of the Dead*.
2. Download and install **Universal Dreamcast Patcher**:  
   ➤ [https://github.com/DerekPascarella/UniversalDreamcastPatcher](https://github.com/DerekPascarella/UniversalDreamcastPatcher)
3. Open your **GDI folder** in the patcher.
4. Select either the **UK** or **German** `.dcp` patch file.
5. Apply the patch.
6. Use the patched version with your preferred **Dreamcast setup** (e.g., emulator or ODE).

## 📌 Notes & Limitations
- These patches only affect **keyboard input mappings** as well as removing the game's region lock.
- No other game content has been modified. 

## Alternatives
- The PC version of "*The Typing of the Dead*" includes a setting to choose between US or UK keyboard layouts

## 👤 Credits
- **Patch Author**: [Widge](https://www.youtube.com/@widge)
- **Patching Tool**: [Universal Dreamcast Patcher](https://github.com/DerekPascarella/UniversalDreamcastPatcher) by [Derek Pascarella](https://github.com/DerekPascarella)
- **Special Thanks**: to @Hinoroni for their wonderful post at the [Dreamcast-Talk Forum](https://www.dreamcast-talk.com/forum/viewtopic.php?p=190356) in which they identified the part of the binary that needed altering to make these patches.
