# Installation

It is expected that Xcode CLI tools, homebrew and ansible are already installed.
To install them run `bin/setup.sh` script.

For local or secret settings, such as computer name, run `cp config.example.yml config.yml` and fill in the variables.

# How to run

`ansible-playbook macos.yml`

# Manual

1. Set resolution to maximum

1. Add `Downloads` and `Applications` to Dock extras

1. Set `Terminal.app` theme
    - Download and run [`Monokai Pro (Filter Spectrum)`](https://github.com/lysyi3m/osx-terminal-themes#monokai-pro-filter-spectrum) theme file
    - Change font to `Meslo LG M for Powerline`

1. Install [Setapp](https://setapp.com/) and following apps with it:
    - Bartender
    - ForkLift
    - iStat Menus
    - Lacona
    - Lungo
    - Mate Translate
    - Mosaic
    - Paste
