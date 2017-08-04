# OpenTTD-TinyPatches
All patches are based on JGR's Patchpack's OpenTTD (https://github.com/JGRennison/OpenTTD-patches)

## OpenTTD-WASD Patch v0.2
For my HHKB2, I want to play OpenTTD using wasd keys instead of arrow keys
So, I made a WASD patch.

### Usage
**You need to modify hotkeys.cfg** (Delete usage of wasd keys likes GLOBAL+A)

### Tested on
* macOS Sierra (maybe availabe on Windows, Linux, etc....)

### TODO
* <s>Make a option menu for wasd feature enable/disable.</s>
* Auto disable hotkeys using wasd keys.
* Configureable keymaps for scrolling mainview. (But need to renaming wasd patch to other :P)
* Code refactoring :)

## OpenTTD-AutoTram Patch v0.1
Town can build tram roads.

### Tested on
* macOS Sierra
* Windows10 compiled by MingW

### TODO
* Make a option menu.
* Make ownership of tram roads.

## OpenTTD-ScrollHotkey Patch v0.1
OpenTTD hotkey system doesn't support scroll keys.
This patch add hotkeys of scroll keys.

### Usage
**You need to modify hotkeys.cfg (scroll_up, scroll_down, scroll_left, scroll_right)**

### Tested on
* macOS Sierra
* Windows10 compiled by MingW
* Ubuntu16.04 with SDL Library
* Ubuntu16.04 with Allegro Library

### TODO
* Code refactoring