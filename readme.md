# Quad cortex configuration

This is a quad cortex configuration for MIDI Commander or Harley Benton MP100 with custom firmware https://github.com/harvie256/midi-commander-custom.

## Setup

- Bank 0: Scenes
  - Buttons can be used to change scenes from A-H
- Bank 1: Presets
  - First 8 presents in "My Presets" bank 1
- Bank 3: Settings
  - A: Toggle tuner
  - B: Toggle gig view
  - 1: Preset mode
  - 2: Scene mode
  - 3: Stomp mode
- Bank 4: FS
  - Buttons enable/bypass footswitches

## Usage

1. Clone this repo
2. Clone midi-commander-custom repo and place it in folder "mini-commander-custom"
3. Follow install instructions in mini-commander-custom repository
4. Flash your device with custom dfu and install the python requirements
5. run `deploy.sh` to transfer quad cortex configs to your device

## Quad Cortex PC message

- A_BankSelect
  - 0 = Factory Presets
  - 1 = My Presets
