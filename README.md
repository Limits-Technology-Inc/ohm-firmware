# Ohm Keyboard Firmware

This repository contains the custom ZMK firmware configuration for the **Ohm keyboard**. It is designed to run on the `nice_nano_v2` microcontroller.

In addition to serving as the ZMK firmware source, this repository is also structured to integrate with [keymap-drawer](https://github.com/caksoylar/keymap-drawer). Keymap-drawer automatically parses the ZMK keymap (`.keymap` files) defined in this repository and generates visual SVGs of the keyboard layout.

## Build Information
This firmware builds against the `nice_nano_v2` board with the `ohm` shield. GitHub Actions handles the automated building of the `ohm-nice_nano_v2-zmk.uf2` and `settings_reset-nice_nano_v2-zmk.uf2` files. To flash, double-click the reset button on your microcontroller and drag-and-drop the generated file onto the flash drive.

### Outputting a keymap visual
Install [keymap-drawer](https://github.com/caksoylar/keymap-drawer) using `pipx install keymap-drawer` and use the generate-visual.bat script to generate a visual of the keymap.
