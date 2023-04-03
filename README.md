# reset-usb
## This program resets all USB ports on a Linux operating system.
This script is a lifesaver when you have USB issues on Linux.
For example, after a USB port power overdraw, your USB ports may become unusable until you reboot. You may see a dmesg error 110. This script lets you reset all your USB ports without resorting to a reboot.

## Installation:
```
git clone https://github.com/gbiz123/reset-usb
cp reset-usb/reset-usb ~/.local/bin
chmod +x ~/.local/bin/reset-usb
```

## Usage:
`sudo reset-usb`

## Credit:
All credit goes to hoijui on unix.stachexchange.com:
https://unix.stackexchange.com/questions/704341/how-to-reset-usb-controllers
