# Installation

It is expected that Xcode CLI tools, homebrew and ansible are already installed.
To install them run `bin/setup.sh` script.

For local or secret settings, such as computer name, run `cp config.example.yml config.yml` and fill in the variables.

# App Store

[MAS CLI](https://github.com/mas-cli/mas) is used to install apps from Mac App Store.
Due to some [problems](https://github.com/mas-cli/mas/issues/164), signing in through CLI is currently impossible.
Because of that, when user is not logged in, App Store is opened and manual sign in is required to proceed.

# How to run

`ansible-playbook macos.yml`

# Manual

1. Set resolution to maximum

1. Add `Downloads` and `Applications` to Dock extras

1. Import iTerm2 profile from `configurations/` folder

1. Install [Setapp](https://setapp.com/) and following apps with it:

   - Bartender
   - BusyCal
   - CleanMyMac X
   - iStat Menus
   - Lungo
   - Mate Translate
   - Mosaic
   - Paste
   - SQLPro Studio
   - PixelSnap

1. Configure SetApp apps

   - For iStat Menus there are exported settings in `configurations/` folder
   - Rest needs to be done manually

1. Add generated ssh key to appropriate services
