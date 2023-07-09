# arch-pkg
A little thing I'm working on for my Arch system. Written in bash.

The whole point of this script is to wrap pacman, flatpak, and yay (AUR helper) in an executable script that makes using them simpler. More just to see what I can do. This script is meant for Arch Linux, but can be used on deravitives, as well

## Installation
I guess this is complete enough to use. To install, just download the arch-pkg file, and move it to `/usr/local/bin` to use it system wide in the terminal. In the case you go to use it, and the terminal gives an error that basically says you don't have permission to use it, a quick `sudo chmod 777 /usr/local/bin/arch-pkg` will fix the issue

## Usage
```Usage: arch-pkg [install|remove|update|search|list] [package manager] [package name]``` 
