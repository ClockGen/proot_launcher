# PR
## Overview
Pr is an all-in-one script to handle installation, configuration and launching of an arch linux container in a termux environment without need for superuser rights.
## Functionality
PR allows to:
- Easily configure the script with interactive wizard
- fetch and install latest archlinuxarm distributive
- Install and launch graphical system (via vnc)
- Integration with termux api for easy file opening inside the container
## Installation
Clone the repo into .shortcuts directory in termux home (for launching it via widget). Termux widget supports subdirs in shortcuts.

cd ~/.shortcuts
git clone https://github.com/ClockGen/proot_launcher

## Usage
It is highly recommended to read integrated help before actually doing anything.  
Script should take care of any missing dependencies and any other kinds of things that need to be interacted with.  
Supported commands:
- -s, --setup
- -i, --install
- -h, --help
## License
Script is written by Buka (ClockGen) and is licensed under the beerware license.
