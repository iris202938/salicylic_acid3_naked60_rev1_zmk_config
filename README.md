# ZMK Configuration for naked60

Generated from QMK info.json

## Keyboard Information
- Name: naked60
- Type: Split
- Normalized Name: naked60
- Board: ble_micro_pro

## Files Structure

### Split Keyboard Files
- boards/shields/naked60/naked60_left.overlay - Left side hardware definition
- boards/shields/naked60/naked60_right.overlay - Right side hardware definition
- boards/shields/naked60/naked60_left.conf - Left side configuration
- boards/shields/naked60/naked60_right.conf - Right side configuration

### Common Files
- boards/shields/naked60/layouts.dtsi - Physical layout definition
- boards/shields/naked60/Kconfig.defconfig - Default configuration
- boards/shields/naked60/Kconfig.shield - Shield configuration
- boards/shields/naked60/naked60.zmk.yml - ZMK metadata
- boards/shields/naked60/naked60.keymap - Shield keymap include
- config/keymap.keymap - Keymap definition
- config/info.json - Keyboard layout information for keymap editors
- config/west.yml - West manifest for ZMK dependencies
- build.yaml - Build configuration for ZMK
- zephyr/module.yml - Zephyr module configuration
- .github/workflows/build.yml - GitHub Actions workflow for building firmware

## Usage
1. Copy all files to your ZMK config repository
2. Customize the keymap in config/keymap.keymap as needed
3. Push to GitHub to trigger automatic firmware builds

## Board Information
This configuration is set up for ble_micro_pro. The board is from sekigon-gonnoc's repository.
